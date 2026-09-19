<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qevpqhbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qevpqhbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-condition" /></template>
