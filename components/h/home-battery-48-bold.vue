<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izjyqdbgb.css';
import '../../css/g/gqhyy7b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izjyqdbgb"/><path class="gqhyy7b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-48-bold" /></template>
