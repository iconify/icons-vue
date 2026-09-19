<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riqh2fbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="riqh2fbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:gateway-complex" /></template>
