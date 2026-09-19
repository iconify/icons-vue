<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeujr8b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zeujr8b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-throw-signal" /></template>
