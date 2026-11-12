<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8czseb2v"/><path class="e_ax9fbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bold-duotone" /></template>
<style>
.e_ax9fbpe {
  fill: currentColor;
  d: path("M7.24316 18.5452C7.8941 20.5504 9.77767 22 11.9998 22C14.222 22 16.1055 20.5504 16.7565 18.5452C13.611 19.1355 10.3886 19.1355 7.24316 18.5452Z");
}

.w8czseb2v {
  fill: currentColor;
  d: path("M18.7491 9V9.7041C18.7491 10.5491 18.9903 11.3752 19.4422 12.0782L20.5496 13.8012C21.5612 15.3749 20.789 17.5139 19.0296 18.0116C14.4273 19.3134 9.57274 19.3134 4.97036 18.0116C3.21105 17.5139 2.43882 15.3749 3.45036 13.8012L4.5578 12.0782C5.00972 11.3752 5.25087 10.5491 5.25087 9.7041V9C5.25087 5.13401 8.27256 2 12 2C15.7274 2 18.7491 5.13401 18.7491 9Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
