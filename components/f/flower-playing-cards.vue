<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(11.735 -.271)" class="d2kvgvbvc"><path class="wcvv2ccrf"/><path class="z83c0u5wb"/><path class="m4euzj36q"/><path class="t_ch8zbii"/><circle class="k47jfqdgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flower-playing-cards" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.k47jfqdgp {
  cx: 14.342px;
  cy: 15.697px;
  r: 11.829px;
  fill: var(--svg-color--fff, #fff);
}

.m4euzj36q {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M40.02 31.23V7.422a3.55 3.55 0 0 0-3.549-3.55H6.109a3.55 3.55 0 0 0-3.548 3.55v33.771c6.174-6.109 30.19-28.2 37.459-9.963");
}

.t_ch8zbii {
  fill: var(--svg-color--a31d2d, #a31d2d);
  d: path("M13.37 7.418c0-1.96 1.587-3.55 3.548-3.55H6.062a3.55 3.55 0 0 0-3.548 3.55v33.771c2.06-2.04 6.109-5.856 10.857-9.363V7.418");
}

.wcvv2ccrf {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M42.572 60.37a4.03 4.03 0 0 1-4.03 4.03H4.036a4.03 4.03 0 0 1-4.03-4.03V4.03A4.03 4.03 0 0 1 4.036 0h34.506a4.03 4.03 0 0 1 4.03 4.03z");
}

.z83c0u5wb {
  fill: var(--svg-color--31444d, #31444d);
  d: path("M9.627 60.37V4.03A4.03 4.03 0 0 1 13.657 0H4.03A4.03 4.03 0 0 0 0 4.03v56.34a4.03 4.03 0 0 0 4.03 4.03h9.627a4.03 4.03 0 0 1-4.03-4.03");
}

</style>
