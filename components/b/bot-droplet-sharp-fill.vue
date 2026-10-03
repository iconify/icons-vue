<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p--4heets"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-droplet-sharp-fill" /></template>
<style>
.p--4heets {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.4944 7.7692C20.1022 9.4451 21 11.6776 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 11.6776 3.8978 9.4451 5.5056 7.7692L12 1L18.4944 7.7692ZM8.882 10.9042L9.593 15.5685L11.5701 15.2671L10.8591 10.6028ZM12.8363 10.3014L13.5473 14.9657L15.5244 14.6643L14.8134 10Z");
}

</style>
