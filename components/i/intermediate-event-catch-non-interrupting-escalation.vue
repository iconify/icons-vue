<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx_alt8-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jx_alt8-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-non-interrupting-escalation" /></template>
