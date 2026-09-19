<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_6qsxbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_6qsxbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dumbbell-alt" /></template>
