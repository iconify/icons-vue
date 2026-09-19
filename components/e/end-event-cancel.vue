<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4myg7bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x4myg7bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-cancel" /></template>
