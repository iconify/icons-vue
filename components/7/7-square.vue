<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d75j04mlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="d75j04mlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:7-square" /></template>
