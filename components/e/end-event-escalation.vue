<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w182swarl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w182swarl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-escalation" /></template>
