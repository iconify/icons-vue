<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzbpy1ouj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzbpy1ouj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:filter" /></template>
