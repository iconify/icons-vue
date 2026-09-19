<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_kxo3vjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g_kxo3vjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:connection" /></template>
