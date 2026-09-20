<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5zf88r9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:change-history-outline-rounded" /></template>
<style>
.x5zf88r9w {
  fill: currentColor;
  d: path("M5.262 19q-.48 0-.702-.416q-.223-.417.025-.82l6.738-10.78q.243-.378.677-.378t.677.378l6.739 10.78q.248.403.025.82q-.224.416-.703.416zm.338-1h12.8L12 7.75zm6.4-5.125");
}

</style>
