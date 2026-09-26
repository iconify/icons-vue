<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vzyo6xb_u"/><path class="snibgdcaa"/><path class="nyf2tdbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-sparkles-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nyf2tdbha {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.2746 6.1869L12.7098 7.2902L13.8131 7.7254C13.9259 7.7698 14 7.8788 14 8C14 8.1212 13.9259 8.2302 13.8131 8.2746L12.7098 8.7098L12.2746 9.8131C12.2302 9.9259 12.1212 10 12 10C11.8788 10 11.7698 9.9259 11.7254 9.8131L11.2902 8.7098L10.1869 8.2746C10.0741 8.2302 10 8.1212 10 8C10 7.8788 10.0741 7.7698 10.1869 7.7254L11.2902 7.2902L11.7254 6.1869C11.7698 6.0741 11.8788 6 12 6C12.1212 6 12.2302 6.0741 12.2746 6.1869Z");
  stroke: none;
}

.snibgdcaa {
  fill: currentColor;
  d: path("M19.5492 1.3739L20.4196 3.5804L22.6261 4.4508C22.8518 4.5397 23 4.7576 23 5C23 5.2424 22.8518 5.4603 22.6261 5.5492L20.4196 6.4196L19.5492 8.6261C19.4603 8.8518 19.2424 9 19 9C18.7576 9 18.5397 8.8518 18.4508 8.6261L17.5804 6.4196L15.3739 5.5492C15.1482 5.4603 15 5.2424 15 5C15 4.7576 15.1482 4.5397 15.3739 4.4508L17.5804 3.5804L18.4508 1.3739C18.5397 1.1482 18.7576 1 19 1C19.2424 1 19.4603 1.1482 19.5492 1.3739Z");
  stroke: none;
}

.vzyo6xb_u {
  d: path("M20 12L20 22L2 22L2 4L10 4M7 4L7 22M15 12L15 22M2 13L20 13M2 8.5L7 8.5M2 17.5L7 17.5M15 17.5L20 17.5");
}

</style>
