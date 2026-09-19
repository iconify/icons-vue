<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gab9z0b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gab9z0b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-none" /></template>
