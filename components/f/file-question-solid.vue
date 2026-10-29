<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tflb91c4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tflb91c4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-question-solid" /></template>
