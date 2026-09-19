<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz94w__1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hz94w__1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:event-subprocess-expanded" /></template>
