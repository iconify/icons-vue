<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrrj-cbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rrrj-cbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:line-h" /></template>
