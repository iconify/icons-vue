<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5362fbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5362fbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:direction-down-right" /></template>
