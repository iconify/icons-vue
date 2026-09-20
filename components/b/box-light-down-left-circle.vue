<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgprs5nyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fgprs5nyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-left-circle" /></template>
