<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bv2g70b9o"/><path class="gafzfy-qb"/><path class="it5n_f80d"/><path class="jomk28w1t"/><path class="r1yenwbix"/><path class="t5yqb5bbx"/><path class="rmvrtivis"/><path class="h03l2ybmq"/><path class="xkk4c8b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cubit-opened" /></template>
<style>
.bv2g70b9o {
  fill: var(--svg-color--7bc0db, #7bc0db);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.gafzfy-qb {
  d: path("m22.429 11.161l8.217 4.92v9.838l-8.217 4.92l-8.217-4.92v-9.838Z");
}

.h03l2ybmq {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M24.877 19.519L22.429 21v2.963l2.448-1.48Z");
}

.it5n_f80d {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M14.879 16.451L22.429 21v9.1l-7.55-4.549Z");
}

.jomk28w1t {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M29.978 16.451L22.428 21v9.1l7.55-4.549Z");
}

.r1yenwbix {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("m14.879 16.451l7.55-4.55l7.55 4.55L22.429 21Z");
}

.rmvrtivis {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M19.98 19.519L22.43 21v2.963l-2.45-1.48Z");
}

.t5yqb5bbx {
  d: path("m22.429 15.076l4.948 2.962v5.925l-4.948 2.962l-4.948-2.962v-5.925Z");
}

.xkk4c8b1v {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("m19.98 19.519l2.45-1.48l2.447 1.48L22.429 21Z");
}

</style>
