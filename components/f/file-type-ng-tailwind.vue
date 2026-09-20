<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGIiKdMcKI"><stop offset="0" class="q_xxb5i9i"/><stop offset="1" class="y-da_dbrl"/></linearGradient></defs><path fill="url(#SVGIiKdMcKI)" transform="translate(2.76 1.986)scale(.11923)" class="lzmzk1bgq"/><path class="nt8p848rf"/><path class="u5s4w2bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ng-tailwind" /></template>
<style>
.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.nt8p848rf {
  fill: var(--svg-color--c3002f, #c3002f);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("m29.239 6.659l-.957 15.013l-9.141-19.687zm-6.332 19.413L16 30.013l-6.908-3.941l1.405-3.405h11.005zM16 9.458l3.619 8.8H12.38zM3.707 21.672L2.76 6.66l10.097-4.673z");
}

.q_xxb5i9i {
  stop-color: var(--svg-color--dd0031, #dd0031);
}

.u5s4w2bsk {
  fill: var(--svg-color--44a8b3, #44a8b3);
  d: path("M16 23a4.726 4.726 0 0 1 5-4c4 0 4.5 3 6.5 3.5A3.21 3.21 0 0 0 31 21a4.726 4.726 0 0 1-5 4c-4 0-4.5-3-6.5-3.5A3.21 3.21 0 0 0 16 23m-5 6a4.726 4.726 0 0 1 5-4c4 0 4.5 3 6.5 3.5A3.21 3.21 0 0 0 26 27a4.726 4.726 0 0 1-5 4c-4 0-4.5-3-6.5-3.5A3.21 3.21 0 0 0 11 29");
}

.y-da_dbrl {
  stop-color: var(--svg-color--c3002f, #c3002f);
}

</style>
