<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i--l_kmzs.css';
import '../../css/j/jfuk8ubuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i--l_kmzs"/><path class="jfuk8ubuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-wui-region" /></template>
