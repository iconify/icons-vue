<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aawtl-1-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="aawtl-1-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:group" /></template>
