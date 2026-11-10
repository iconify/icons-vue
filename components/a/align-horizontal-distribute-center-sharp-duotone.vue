<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gszuqeb8t"/><path class="nnef0sluv"/><path class="vdxsixsjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-center-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gszuqeb8t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 4C10.552 4 11 4.448 11 5V19C11 19.552 10.552 20 10 20H4C3.448 20 3 19.552 3 19V5C3 4.448 3.448 4 4 4H10ZM20 6C20.552 6 21 6.448 21 7V17C21 17.552 20.552 18 20 18H14C13.448 18 13 17.552 13 17V7C13 6.448 13.448 6 14 6H20Z");
}

.nnef0sluv {
  d: path("M8 19V23H6V19H8ZM18 17V23H16V17H18ZM18 1V7H16V1H18Z");
}

.vdxsixsjw {
  d: path("M8 1V5H6V1H8Z");
}

</style>
