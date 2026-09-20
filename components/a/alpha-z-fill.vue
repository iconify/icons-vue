<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0cpzlb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="j0cpzlb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-z-fill" /></template>
