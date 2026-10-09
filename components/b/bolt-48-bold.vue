<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgy96wbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgy96wbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-48-bold" /></template>
