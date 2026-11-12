<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="on5-pc9rb"/><path class="v2poh3i8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.on5-pc9rb {
  d: path("M17.9054 3.92871L17.9376 3.99951C18.1717 4.71004 17.7035 6.13109 17.2354 6.84162C17.0658 7.09898 16.6812 7.4185 16.2597 7.72137C15.3092 8.40428 14.1097 8.74205 13.4998 9.99951C13.3255 10.359 13.3329 10.7103 13.4168 11.0158C13.4771 11.2354 13.5156 11.474 13.5162 11.7075C13.5182 12.4624 12.7547 13.0078 11.9998 12.9995C10.0355 12.9781 8.74968 11.3951 8.57465 9.44688C8.38739 7.36267 6.78008 5.42057 5.99984 4.71004L5.59668 4.31856");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.v2poh3i8h {
  d: path("M21.9291 13.2227C21.619 14.2699 21.1699 16.3774 17.7182 16.4134C17.7182 16.4134 14.4246 16.4134 13.4365 18.2755C12.6837 19.694 13.0659 21.2251 13.3885 21.904");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
