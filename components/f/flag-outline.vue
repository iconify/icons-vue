<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmrx7_tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flag-outline" /></template>
<style>
.qwmrx7_tf {
  fill: currentColor;
  d: path("M6 20.5V5h7.192l.4 2H19v8h-5.192l-.4-2H7v7.5zm8.65-6.5H18V8h-5.25l-.4-2H7v6h7.25z");
}

</style>
