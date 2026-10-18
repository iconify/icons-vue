<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3a2h2b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3a2h2b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lightbulb" /></template>
