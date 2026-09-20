<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-1zsbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="j5-1zsbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:cloud-down" /></template>
