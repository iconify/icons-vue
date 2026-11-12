<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4x6s3rwq"/><path class="qj7yj4vww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-right-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qj7yj4vww {
  d: path("M12.5947 7.61792V4.87257C12.5947 3.75082 12.5947 3.18995 12.9422 3.03474C13.2897 2.87953 13.7111 3.25215 14.554 3.9974L19.2301 8.13188L19.2302 8.13189C21.0767 9.76455 22 10.5809 22 11.6325C22 12.6842 21.0767 13.5005 19.2302 15.1332L19.2301 15.1332L14.554 19.2677C13.7111 20.0129 13.2897 20.3856 12.9422 20.2303C12.5947 20.0751 12.5947 19.5143 12.5947 18.3925V15.6472");
}

.y4x6s3rwq {
  stroke-linejoin: round;
  d: path("M19.2301 8.13188L14.554 3.9974C13.7111 3.25215 13.2897 2.87953 12.9422 3.03474C12.5947 3.18995 12.5947 3.75082 12.5947 4.87257V7.61792C8.27835 7.61792 2 10.2943 2 21C3.76579 17.6545 8.35683 15.6472 12.5947 15.6472V18.3925C12.5947 19.5143 12.5947 20.0751 12.9422 20.2303C13.2897 20.3856 13.7111 20.0129 14.554 19.2677L19.2301 15.1332C21.0767 13.5005 22 12.6842 22 11.6325C22 10.5809 21.0767 9.76455 19.2301 8.13188Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
