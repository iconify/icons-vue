<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxnva97bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rxnva97bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:intermediate-event-catch-non-interrupting-timer" /></template>
