<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3zufxbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a3zufxbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-terminate" /></template>
