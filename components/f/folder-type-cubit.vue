<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc1vmsbgn"/><path class="mp5brvx2o"/><path class="i8rwvx3ay"/><path class="t4bke_bex"/><path class="odioojb1l"/><path class="gtwwehblu"/><path class="cwhy03bbm"/><path class="w_a_q2f6f"/><path class="c3fxcsb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cubit" /></template>
<style>
.c3fxcsb0o {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("m19.979 19.519l2.451-1.48l2.447 1.48L22.429 21Z");
}

.cwhy03bbm {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M19.979 19.519L22.43 21v2.963l-2.45-1.48Z");
}

.gtwwehblu {
  d: path("m22.428 15.076l4.948 2.962v5.925l-4.948 2.962l-4.948-2.962v-5.925Z");
}

.i8rwvx3ay {
  fill: var(--svg-color--82eddf, #82eddf);
  d: path("M14.878 16.451L22.429 21v9.1l-7.55-4.549Z");
}

.mp5brvx2o {
  d: path("m22.428 11.161l8.217 4.92v9.838l-8.216 4.92l-8.217-4.92v-9.838Z");
}

.odioojb1l {
  fill: var(--svg-color--0084c1, #0084c1);
  d: path("m14.878 16.451l7.551-4.55l7.549 4.55L22.429 21Z");
}

.qc1vmsbgn {
  fill: var(--svg-color--55a3bf, #55a3bf);
  d: path("M27.417 5.5H18.19l-2.083 4.2H4.5v16.8h25v-21Zm0 4.2h-8.135l1.091-2.1h7.044Z");
}

.t4bke_bex {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M29.977 16.451L22.427 21v9.1l7.55-4.549Z");
}

.w_a_q2f6f {
  fill: var(--svg-color--00d3b9, #00d3b9);
  d: path("M24.876 19.519L22.428 21v2.963l2.448-1.48Z");
}

</style>
