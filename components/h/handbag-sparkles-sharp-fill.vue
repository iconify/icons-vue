<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ian_mmbvf"/><path class="icm1-3ppw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-sparkles-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ian_mmbvf {
  d: path("M8 7C8 4.7909 9.7909 3 12 3C14.2091 3 16 4.7909 16 7M12 21L4 21L4 7L20 7L20 13");
}

.icm1-3ppw {
  fill: currentColor;
  d: path("M17.5492 14.3739L18.4196 16.5804L20.6261 17.4508C20.8518 17.5397 21 17.7576 21 18C21 18.2424 20.8518 18.4603 20.6261 18.5492L18.4196 19.4196L17.5492 21.6261C17.4603 21.8518 17.2424 22 17 22C16.7576 22 16.5397 21.8518 16.4508 21.6261L15.5804 19.4196L13.3739 18.5492C13.1482 18.4603 13 18.2424 13 18C13 17.7576 13.1482 17.5397 13.3739 17.4508L15.5804 16.5804L16.4508 14.3739C16.5397 14.1482 16.7576 14 17 14C17.2424 14 17.4603 14.1482 17.5492 14.3739ZM9.8433 11.2337L10.3873 12.6127L11.7663 13.1567C11.9074 13.2123 12 13.3485 12 13.5C12 13.6515 11.9074 13.7877 11.7663 13.8433L10.3873 14.3873L9.8433 15.7663C9.7877 15.9074 9.6515 16 9.5 16C9.3485 16 9.2123 15.9074 9.1567 15.7663L8.6127 14.3873L7.2337 13.8433C7.0926 13.7877 7 13.6515 7 13.5C7 13.3485 7.0926 13.2123 7.2337 13.1567L8.6127 12.6127L9.1567 11.2337C9.2123 11.0926 9.3485 11 9.5 11C9.6515 11 9.7877 11.0926 9.8433 11.2337Z");
  stroke: none;
}

</style>
