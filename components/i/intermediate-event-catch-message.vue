<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flwdm6b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="flwdm6b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-message" /></template>
