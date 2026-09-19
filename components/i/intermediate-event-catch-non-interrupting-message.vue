<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv6qv8ips.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jv6qv8ips"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-non-interrupting-message" /></template>
