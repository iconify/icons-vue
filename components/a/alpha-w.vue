<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2s99bc2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="o2s99bc2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-w" /></template>
