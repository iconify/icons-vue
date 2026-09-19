<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ds15qxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h2ds15qxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event" /></template>
