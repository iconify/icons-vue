<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmy5q6b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmy5q6b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:kanban-check" /></template>
