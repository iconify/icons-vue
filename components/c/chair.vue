<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyqblitaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1792};
const content = `<path class="fyqblitaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:chair" /></template>
