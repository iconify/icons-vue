<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpvi0b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bee-sharp" /></template>
<style>
.mtpvi0b7l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7C6.5817 7 3 10.5817 3 15L3 16C3 16.5523 3.4477 17 4 17C8.4183 17 12 13.4183 12 9L12 8C12 7.4477 11.5523 7 11 7ZM13 7C17.4183 7 21 10.5817 21 15L21 16C21 16.5523 20.5523 17 20 17C15.5817 17 12 13.4183 12 9L12 8C12 7.4477 12.4477 7 13 7ZM15 6C15 4.3431 13.6569 3 12 3C10.3431 3 9 4.3431 9 6C9 6.5523 9.4477 7 10 7L14 7C14.5523 7 15 6.5523 15 6ZM9.8787 3.8787L9.5 3.5L8 2L7.7071 1.7071M14.1213 3.8787L14.5 3.5L16 2L16.2929 1.7071M7.4245 16.2358L7.5 16.5C7.8333 17.6667 9.2 20.4 12 22C14.8 20.4 16.1667 17.6667 16.5 16.5L16.5755 16.2358");
}

</style>
