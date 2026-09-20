<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukfw4ibyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ukfw4ibyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-j-fill" /></template>
