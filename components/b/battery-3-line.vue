<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq_mcpbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq_mcpbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-3-line" /></template>
