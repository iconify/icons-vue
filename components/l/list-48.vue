<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygo23sqro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygo23sqro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-48" /></template>
