<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d05sqwksi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d05sqwksi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:compass-south-east" /></template>
