<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf863cbsv"/><path class="zfmuiycex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-up-bold-duotone" /></template>
<style>
.nf863cbsv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5303 15.5303C6.3158 15.7448 5.99321 15.809 5.71296 15.6929C5.4327 15.5768 5.24997 15.3033 5.24997 15V5.99997C5.24997 5.58576 5.58576 5.24997 5.99997 5.24997L15 5.24997C15.3033 5.24997 15.5768 5.4327 15.6929 5.71296C15.809 5.99321 15.7448 6.3158 15.5303 6.5303L6.5303 15.5303Z");
}

.zfmuiycex {
  fill: currentColor;
  d: path("M18.5303 17.4697C18.8232 17.7626 18.8232 18.2374 18.5303 18.5303C18.2374 18.8232 17.7626 18.8232 17.4697 18.5303L10.5 11.5607L11.5607 10.5L18.5303 17.4697Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
