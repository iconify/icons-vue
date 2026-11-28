<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew7pgvbcs.css';
import '../../css/i/i6yti7l8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew7pgvbcs secondary"/><path class="i6yti7l8q primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-left-duo" /></template>
