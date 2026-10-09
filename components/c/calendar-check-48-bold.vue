<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwjkdv1oe.css';
import '../../css/c/crft-ebma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="crft-ebma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-check-48-bold" /></template>
