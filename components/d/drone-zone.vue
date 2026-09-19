<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8qgz5yfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8qgz5yfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:drone-zone" /></template>
