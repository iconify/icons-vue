<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf92albeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hf92albeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:coin-platinum" /></template>
