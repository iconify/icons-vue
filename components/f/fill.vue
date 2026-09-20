<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-3ycde5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="l-3ycde5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:fill" /></template>
