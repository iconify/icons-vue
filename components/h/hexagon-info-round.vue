<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8q5e8axb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8q5e8axb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-info-round" /></template>
