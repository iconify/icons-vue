<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhr271wtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nhr271wtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:gateway-none" /></template>
