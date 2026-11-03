<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yyx52ac3l"/><path class="d_6oim15i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmarks-sharp-two-tone" /></template>
<style>
.d_6oim15i {
  d: path("M4 7L16 7L16 21.2488L15.6602 22L14.8444 21.8797L10.6083 19.6386L10.0001 19.2475L9.3917 19.6386L5.1556 21.8797L4.3398 22L4 21.2488L4 7ZM20 18.1987L20 2L8.8455 2L7.9792 3.4998");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yyx52ac3l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6L16 6C16.5523 6 17 6.4477 17 7L17 21.2488C17 21.3909 16.9697 21.5314 16.9111 21.6609L16.5713 22.4121C16.4094 22.77 16.053 23 15.6602 23C15.6114 23 15.5626 22.9964 15.5143 22.9893L14.6985 22.869C14.5861 22.8524 14.4772 22.8168 14.3768 22.7636L10.1407 20.5225C10.1157 20.5093 10.0912 20.495 10.0674 20.4797L10 20.4364L9.9324 20.4798C9.9087 20.4951 9.8843 20.5093 9.8593 20.5225L5.6232 22.7636C5.5228 22.8168 5.4139 22.8524 5.3015 22.869L4.4857 22.9893C4.4374 22.9964 4.3886 23 4.3398 23C3.947 23 3.5906 22.77 3.4287 22.4121L3.0889 21.6609C3.0303 21.5314 3 21.3909 3 21.2488L3 7C3 6.4477 3.4477 6 4 6Z");
  stroke: none;
}

</style>
