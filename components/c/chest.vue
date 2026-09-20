<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5-fw6cio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="e5-fw6cio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chest" /></template>
