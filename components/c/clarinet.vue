<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8tg9wbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clarinet" /></template>
<style>
.j8tg9wbdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14H6.1547C6.0522 14 5.9503 13.9842 5.8525 13.9533L2.6978 12.9533C1.7674 12.6583 1.7674 11.3417 2.6978 11.0467L5.8525 10.0467C5.9503 10.0158 6.0522 10 6.1547 10H8H15C18 10 19.2322 8.3536 20.2929 7.2929C20.4804 7.1054 20.7348 7 21 7C21.5523 7 22 7.4477 22 8V16C22 16.5523 21.5523 17 21 17C20.7348 17 20.4804 16.8946 20.2929 16.7071C19.2322 15.6464 18 14 15 14ZM9 10V7.5M13 10V7.5");
}

</style>
