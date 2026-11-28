<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdx32lbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdx32lbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flip-vertical-solid" /></template>
