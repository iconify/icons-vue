<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci3tn5bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ci3tn5bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-compensation" /></template>
