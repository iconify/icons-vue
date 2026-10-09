<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpjq1ubkk.css';
import '../../css/m/mbu6h6bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpjq1ubkk"/><path class="mbu6h6bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-fire-48-bold" /></template>
