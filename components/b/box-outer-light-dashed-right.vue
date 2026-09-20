<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8av0dbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v8av0dbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-right" /></template>
