<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn7c2nbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jn7c2nbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:legend-20-bold" /></template>
