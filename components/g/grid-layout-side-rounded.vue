<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oto2jq9jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-layout-side-rounded" /></template>
<style>
.oto2jq9jm {
  fill: currentColor;
  d: path("M20 20V4zM5.615 20h6.27q.67 0 1.143-.472q.472-.472.472-1.143V5.615q0-.67-.472-1.143Q12.556 4 11.885 4h-6.27q-.67 0-1.143.472Q4 4.944 4 5.616v12.769q0 .67.472 1.143q.472.472 1.144.472M20 18.384V5.616q0-.672-.472-1.144T18.385 4h-2.27q-.67 0-1.143.472q-.472.472-.472 1.144v12.769q0 .67.472 1.143q.472.472 1.144.472h2.269q.67 0 1.143-.472q.472-.472.472-1.143");
}

</style>
