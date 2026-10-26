<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyit_btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flashlight" /></template>
<style>
.aeyit_btq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12L10 12M17 7L17 17M4 16L9.7639 16C11.2344 16 12.6847 16.3424 14 17C15.3153 17.6576 16.7656 18 18.2361 18L20 18C21.1046 18 22 17.1046 22 16L22 8C22 6.8954 21.1046 6 20 6L18.2361 6C16.7656 6 15.3153 6.3424 14 7C12.6847 7.6576 11.2344 8 9.7639 8L4 8C2.8954 8 2 8.8954 2 10L2 14C2 15.1046 2.8954 16 4 16Z");
}

</style>
