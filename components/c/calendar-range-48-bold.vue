<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwjkdv1oe.css';
import '../../css/c/ccoa7kjog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="ccoa7kjog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-range-48-bold" /></template>
