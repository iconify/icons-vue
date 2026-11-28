<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ohpel8bel"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohpel8bel {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.6084 20.7284C19.9635 22.0721 18.5901 23 17 23H7C4.7909 23 3 21.2091 3 19V7C3.0001 5.9382 3.4176 4.9573 4.1121 4.2321L20.6084 20.7284ZM8.024 3.7814L6.5336 2.291C7.0839 1.4975 7.9978 1.0001 9 1H15C16.3075 1.0001 17.4646 1.8466 17.8604 3.0928C19.694 3.4972 20.9998 5.1223 21 7V14.3431C21 14.8954 20.5523 15.3431 20 15.3431C19.7239 15.3431 19.4739 15.2312 19.2929 15.0503L11.9498 7.7071C11.7688 7.5262 11.6569 7.2762 11.6569 7C11.6569 6.4477 12.1046 6 12.6569 6H15C15.5523 6 16 5.5523 16 5V4C16 3.4477 15.5523 3 15 3H9C8.5228 3 8.1237 3.3342 8.024 3.7814Z");
  stroke: none;
}

</style>
