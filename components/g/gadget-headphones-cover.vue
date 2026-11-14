<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyjoovb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gadget-headphones-cover" /></template>
<style>
.oyjoovb2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.202 12.202q.475-.475 1.048-.713q.004-3.203 2.27-5.469Q8.79 3.75 12 3.75t5.48 2.27q2.266 2.266 2.27 5.469q.573.238 1.048.713q.952.952.952 2.298V16q0 1.346-.952 2.298t-2.298.952q-3.25 0-3.25-3.25v-.75q0 2.386-2.998 3.456q-.122.044-.252.044t-.252-.044Q8.75 17.636 8.75 15.25V16q0 3.25-3.25 3.25T2.25 16v-1.5q0-1.346.952-2.298M8.75 14.5v-1q0-.112.033-.22q.033-.107.096-.2t.151-.164t.191-.112l2.5-1q.135-.054.279-.054t.279.054l2.5 1q.104.041.191.112q.088.07.151.164q.063.093.096.2t.033.22v1q0-3.12 2.996-3.245q-.083-2.431-1.827-4.174Q14.589 5.25 12 5.25T7.581 7.081q-1.744 1.743-1.827 4.174Q8.75 11.38 8.75 14.5");
}

</style>
