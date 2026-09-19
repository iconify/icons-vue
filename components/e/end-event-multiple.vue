<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ca4z9jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p2ca4z9jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-multiple" /></template>
