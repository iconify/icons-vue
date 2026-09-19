<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipyo4j7ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ipyo4j7ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-link" /></template>
