<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyo9g4bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyo9g4bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:kanban-view" /></template>
