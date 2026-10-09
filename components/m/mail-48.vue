<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxbs21b9m.css';
import '../../css/d/dekgiyoss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxbs21b9m"/><path class="dekgiyoss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-48" /></template>
