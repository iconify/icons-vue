<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txaxgvbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-plane" /></template>
<style>
.txaxgvbdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h.25q.75 0 1.17.62l2.16 3.26q.42.62 1.17.62h7.25q.75 0 .75.75v3q0 .75-.75.75H15q-.75 0-1.14.64l-2.72 4.47q-.39.64-1.14.64h-.75q-.75 0-.59-.73l.93-4.29q.16-.73-.59-.73H5.75q-.75 0-1.16-.63l-1.43-2.24q-.41-.63-.41-1.38v-4q0-.75.75-.75m14.05 2.81l1.9-4.37q.3-.69.52.03l1.06 3.56q.22.72-.52.86l-2.52.47q-.74.14-.44-.55");
}

</style>
