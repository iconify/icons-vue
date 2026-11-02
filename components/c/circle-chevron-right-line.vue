<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr4tq0brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr4tq0brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-right-line" /></template>
