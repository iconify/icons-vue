<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc715-kwz.css';
import '../../css/h/hustz32ji.css';
import '../../css/a/aqstzpbjn.css';
import '../../css/h/h48zvybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yc715-kwz"/><path class="hustz32ji wm-a"/><path class="aqstzpbjn wm-a"/><path class="h48zvybiq wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:clipboard-list" /></template>
