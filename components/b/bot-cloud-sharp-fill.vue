<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df6opobwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-cloud-sharp-fill" /></template>
<style>
.df6opobwf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 20L18 20C20.6233 20 23 17.6233 23 15C23 12.6937 21.163 10.578 18.9365 10.1004C18.4644 6.7612 15.4245 4 12 4C8.5755 4 5.5356 6.7612 5.0635 10.1004C2.837 10.578 1 12.6937 1 15C1 17.6233 3.3767 20 6 20ZM8.882 10.9042L10.8591 10.6028L11.5701 15.2671L9.593 15.5685L8.882 10.9042ZM12.8363 10.3014L14.8134 10L15.5244 14.6643L13.5473 14.9657L12.8363 10.3014Z");
}

</style>
