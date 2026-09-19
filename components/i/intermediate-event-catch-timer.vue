<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euc22-b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="euc22-b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-timer" /></template>
