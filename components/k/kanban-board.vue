<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh7ourc9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh7ourc9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:kanban-board" /></template>
