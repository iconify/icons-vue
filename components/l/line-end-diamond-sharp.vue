<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smfebfddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-diamond-sharp" /></template>
<style>
.smfebfddh {
  fill: currentColor;
  d: path("m15 16.77l-4.27-4.27H3.078v-1h7.654L15 7.23L19.77 12z");
}

</style>
