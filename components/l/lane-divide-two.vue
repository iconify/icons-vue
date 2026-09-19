<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwi8gpbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iwi8gpbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:lane-divide-two" /></template>
