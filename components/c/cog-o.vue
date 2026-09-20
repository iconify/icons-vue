<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmx758bjt.css';
import '../../css/g/g6rzu6bev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmx758bjt"/><path class="g6rzu6bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cog-o" /></template>
