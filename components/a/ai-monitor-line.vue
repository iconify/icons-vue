<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs60f7byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs60f7byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-monitor-line" /></template>
