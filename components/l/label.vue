<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oinc0gbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="oinc0gbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:label" /></template>
