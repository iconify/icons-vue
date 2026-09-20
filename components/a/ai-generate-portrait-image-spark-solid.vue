<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tikjj3y7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tikjj3y7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:ai-generate-portrait-image-spark-solid" /></template>
