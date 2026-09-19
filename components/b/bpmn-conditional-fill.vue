<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwvgzj0ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uwvgzj0ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bpmn-conditional-fill" /></template>
