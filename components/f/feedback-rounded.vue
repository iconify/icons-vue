<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulh-5-hkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feedback-rounded" /></template>
<style>
.ulh-5-hkn {
  fill: currentColor;
  d: path("m6.077 17l-1.704 1.704q-.379.379-.876.171T3 18.133V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v10.769q0 .69-.463 1.153T19.385 17zM12 14.423q.262 0 .439-.177q.176-.177.176-.438t-.177-.439t-.438-.177t-.438.177t-.177.439t.177.438t.438.177m.357-3.105q.143-.144.143-.356V5.885q0-.213-.144-.357t-.357-.143t-.356.143t-.143.357v5.077q0 .212.144.356t.357.144t.356-.144");
}

</style>
