<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r32aubcob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r32aubcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:compass-gloss" /></template>
