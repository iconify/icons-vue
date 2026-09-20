<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnouhwtht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comma-24-filled" /></template>
<style>
.dnouhwtht {
  fill: currentColor;
  d: path("M14.2 12.342a4 4 0 1 1 1.765-3.873c.365 1.792.507 3.947-.207 5.898c-.766 2.09-2.464 3.804-5.505 4.6a1 1 0 0 1-.506-1.934c2.46-.644 3.61-1.93 4.133-3.354c.155-.425.26-.874.32-1.338");
}

</style>
