<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elgjl_fle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="elgjl_fle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:end-event-none" /></template>
