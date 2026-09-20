<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9dykebcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9dykebcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chip-line" /></template>
