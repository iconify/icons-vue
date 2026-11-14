<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo7c_ec-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-bowl-empty" /></template>
<style>
.xo7c_ec-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.499v.003q0 .347.15.661l2.125 8.029l.013.045q.671 2.013 2.712 2.013h9.5q2.041 0 2.712-2.013l.013-.045L21.6 9.163q.15-.315.15-.664q.002-1.605-3.184-2.49q-2.735-.76-6.566-.76t-6.566.76q-3.184.885-3.184 2.49m3.719 8.285l-1.63-6.155q.49.194 1.095.362q2.735.76 6.566.76t6.566-.76q.605-.168 1.095-.362l-1.63 6.155q-.332.966-1.281.966h-9.5q-.949 0-1.281-.966");
}

</style>
