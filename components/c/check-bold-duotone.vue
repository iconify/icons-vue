<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoshjbpvd"/><path class="bt37pjbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-bold-duotone" /></template>
<style>
.aoshjbpvd {
  fill: currentColor;
  d: path("M18.4697 6.46973C18.7626 6.17684 19.2373 6.17684 19.5302 6.46973C19.8231 6.76262 19.8231 7.23738 19.5302 7.53028L9.53022 17.5303C9.23732 17.8232 8.76256 17.8232 8.46967 17.5303C8.17678 17.2374 8.17678 16.7626 8.46967 16.4697L18.4697 6.46973Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.bt37pjbzd {
  fill: currentColor;
  d: path("M4.46967 12.4697C4.76256 12.1768 5.23732 12.1768 5.53022 12.4697L9.53022 16.4697C9.82311 16.7626 9.82311 17.2374 9.53022 17.5303C9.23732 17.8232 8.76256 17.8232 8.46967 17.5303L4.46967 13.5303C4.17678 13.2374 4.17678 12.7626 4.46967 12.4697Z");
}

</style>
