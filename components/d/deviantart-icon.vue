<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":414};
const content = `<path class="rk_lcpd0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:deviantart-icon" /></template>
<style>
.rk_lcpd0f {
  fill: var(--svg-color--45ad47, #45ad47);
  d: path("M256 75.206V.004h-75.203l-7.505 7.57l-35.485 67.624l-11.158 7.528H0V186h69.626l6.201 7.5L0 338.396V413.6h75.201l7.507-7.567l35.487-67.627l11.156-7.526H256V227.605h-69.626l-6.195-7.551z");
}

</style>
