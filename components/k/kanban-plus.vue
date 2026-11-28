<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl_upwb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl_upwb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:kanban-plus" /></template>
