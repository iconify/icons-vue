<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu4v0ccni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vu4v0ccni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-throw-compensation" /></template>
