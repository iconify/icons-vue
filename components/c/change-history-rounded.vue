<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1c-rtbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:change-history-rounded" /></template>
<style>
.z1c-rtbqo {
  fill: currentColor;
  d: path("M5.262 19q-.48 0-.702-.416q-.223-.417.025-.82l6.738-10.78q.243-.378.677-.378t.677.378l6.739 10.78q.248.403.025.82q-.224.416-.703.416z");
}

</style>
