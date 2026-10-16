<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5rak2bbx.css';
import '../../css/q/qnvn8ia7m.css';
import '../../css/v/vai4pdqog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5rak2bbx"/><path class="qnvn8ia7m"/><path class="vai4pdqog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ceiling-light-48-bold" /></template>
