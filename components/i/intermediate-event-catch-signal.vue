<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcp-m_d0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jcp-m_d0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-signal" /></template>
