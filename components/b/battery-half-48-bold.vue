<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia0elbbtb.css';
import '../../css/z/zwjjpmnxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia0elbbtb"/><path class="zwjjpmnxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-half-48-bold" /></template>
