<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-o60sb2m.css';
import '../../css/l/lr2ntzbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-o60sb2m"/><path class="lr2ntzbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ammonia-48" /></template>
