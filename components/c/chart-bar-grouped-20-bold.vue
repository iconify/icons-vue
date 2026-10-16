<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4mjjratt.css';
import '../../css/f/fnu7wqbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4mjjratt"/><path class="fnu7wqbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-grouped-20-bold" /></template>
