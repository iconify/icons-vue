<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9xujbkcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-sharp" /></template>
<style>
.d9xujbkcd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 10C4 8.8954 4.8954 8 6 8L8 8L8 18L6 18C4.8954 18 4 17.1046 4 16L4 10ZM20 10C20 8.8954 19.1046 8 18 8L16 8L16 18L18 18C19.1046 18 20 17.1046 20 16L20 10ZM4 10C4 5.5817 7.5817 2 12 2C16.4183 2 20 5.5817 20 10M18 18L18 22L11 22");
}

</style>
