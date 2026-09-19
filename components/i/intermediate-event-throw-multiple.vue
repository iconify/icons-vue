<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey1cel3wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ey1cel3wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-throw-multiple" /></template>
