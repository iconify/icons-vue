<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q-kpa9bhz"/><path class="nrw_deb6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-end-horizontal-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nrw_deb6b {
  d: path("M20 9C20.552 9 21 9.448 21 10V18C21 18.552 20.552 19 20 19H14C13.448 19 13 18.552 13 18V10C13 9.448 13.448 9 14 9H20Z");
}

.q-kpa9bhz {
  d: path("M23 21V23H1V21H23ZM10 1C10.552 1 11 1.448 11 2V18C11 18.552 10.552 19 10 19H4C3.448 19 3 18.552 3 18V2C3 1.448 3.448 1 4 1H10Z");
}

</style>
