<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9f7cs6wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="r9f7cs6wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-k-fill" /></template>
