<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dds2i6bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dds2i6bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-l-fill" /></template>
