<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah89dicoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ah89dicoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-down-left" /></template>
