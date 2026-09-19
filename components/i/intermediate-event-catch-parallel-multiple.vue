<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjjz6w-nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gjjz6w-nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-parallel-multiple" /></template>
