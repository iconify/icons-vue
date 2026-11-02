<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmieo0byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmieo0byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hight-beam-headlights-fill" /></template>
