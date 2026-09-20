<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmaa6ub8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zmaa6ub8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-w-fill" /></template>
