<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs7c-ub3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zs7c-ub3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:crop" /></template>
