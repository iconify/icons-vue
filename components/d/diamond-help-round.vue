<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhym1fszd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhym1fszd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-help-round" /></template>
