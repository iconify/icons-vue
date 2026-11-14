<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8rt3dx5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deal-approval" /></template>
<style>
.y8rt3dx5q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 6q0-3.75 3.75-3.75T15.75 6q0 2.372-1.5 3.243v3.007h2q1.036 0 1.768.732t.732 1.768v.5q0 .541-.2 1h.401q1.286 0 1.939 1.109q.652 1.108.028 2.233l-.833 1.5q-.643 1.158-1.968 1.158H5.049q-1.286 0-1.939-1.109q-.652-1.108-.028-2.233l.833-1.5q.517-.932 1.475-1.114q-.14-.452-.14-1.044v-.5q0-2.5 2.5-2.5h2V9.243Q8.25 8.372 8.25 6m4.5 6.25V9.708q-.354.042-.75.042t-.75-.042v2.542z");
}

</style>
