<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9_cmhbvy.css';
import '../../css/y/yu8tkqs3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="q9_cmhbvy"/><path class="yu8tkqs3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:light-skin-tone" /></template>
