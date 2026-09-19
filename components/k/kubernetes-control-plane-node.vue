<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eje_24crj.css';
import '../../css/e/e35vx9b8n.css';
import '../../css/x/x8r3bo3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eje_24crj"/><path class="e35vx9b8n"/><path class="x8r3bo3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:kubernetes-control-plane-node" /></template>
