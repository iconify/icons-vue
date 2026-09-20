<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2yh6lbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c2yh6lbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-u" /></template>
