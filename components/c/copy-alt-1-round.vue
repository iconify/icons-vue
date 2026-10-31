<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jokhamznc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jokhamznc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:copy-alt-1-round" /></template>
