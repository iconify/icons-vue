<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e0z-6ee1n.css';
import '../../css/q/qafvmubuv.css';
import '../../css/j/jyumk6b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0z-6ee1n"/><path class="qafvmubuv"/><path class="jyumk6b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-linear" /></template>
