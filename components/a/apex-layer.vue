<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8maa73ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8maa73ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:apex-layer" /></template>
