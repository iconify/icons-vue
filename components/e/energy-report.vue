<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrebgjc0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jrebgjc0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:energy-report" /></template>
