<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se4exfb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ban-sharp-fill" /></template>
<style>
.se4exfb1h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.9372 1 23 6.0628 23 12C23 17.9372 17.9372 23 12 23C6.0628 23 1 17.9372 1 12C1 6.0628 6.0628 1 12 1ZM4.9289 6.3431L17.6569 19.0711L19.0711 17.6569L6.3431 4.9289L4.9289 6.3431Z");
}

</style>
