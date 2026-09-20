<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bv2g70b9o"/><path class="ntuumre2a"/><path class="k8qxfilja"/><path class="imk-hfbnk"/><path class="g98vaobit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-bloc-opened" /></template>
<style>
.bv2g70b9o {
  fill: var(--svg-color--7bc0db, #7bc0db);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.g98vaobit {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M22.429 28.857V21l6.804-3.929v7.858z");
}

.imk-hfbnk {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M15.624 17.071v7.858l6.805 3.928V21z");
}

.k8qxfilja {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("M15.624 17.071L22.429 21l6.804-3.929l-6.804-3.928z");
}

.ntuumre2a {
  d: path("m31 26l-8.571 5l-8.572-5V16l8.572-5L31 16z");
}

</style>
