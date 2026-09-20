<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3f6uhjag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cottage-outline" /></template>
<style>
.p3f6uhjag {
  fill: currentColor;
  d: path("M5 20v-9.144l-1.934 1.49l-.604-.792L5 9.6V6.962h1v1.863l6-4.575l9.539 7.304l-.605.787L19 10.856V20zm1-1h4.616v-4.77h2.769V19H18v-8.9l-6-4.575L6 10.1zM5 5.77q0-.905.577-1.549t1.654-.644q.656 0 .943-.345t.288-.848h1q0 .904-.578 1.549q-.576.644-1.653.644q-.656 0-.944.345T6 5.769zM6 19h12z");
}

</style>
