<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5jp5rer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-lira-outline-rounded" /></template>
<style>
.jw5jp5rer {
  fill: currentColor;
  d: path("M9.5 19.192v-4.246l-2.225 1.387q-.27.17-.522.015q-.253-.156-.253-.448q0-.14.067-.25t.177-.177L9.5 13.744v-3.523l-2.244 1.406q-.25.165-.503.015T6.5 11.2q0-.14.058-.25t.161-.177L9.5 9.019V4.5q0-.213.143-.357T10 4t.357.143t.143.357v3.904l3.244-2.031q.25-.171.503-.018t.253.445q0 .14-.067.25t-.177.177L10.5 9.606v3.523l3.244-2.031q.25-.171.503-.018t.253.445q0 .14-.067.25t-.177.177L10.5 14.331V19h.5q1.971 0 3.52-1.248q1.547-1.248 1.886-3.298q.03-.202.199-.328T16.98 14q.213 0 .347.15t.103.352q-.35 2.37-2.147 3.934T11 20h-.692q-.348 0-.578-.23t-.23-.578");
}

</style>
