<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgfptlk-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mgfptlk-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-redo-spark-solid" /></template>
