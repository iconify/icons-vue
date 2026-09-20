<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoe6gv-um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoe6gv-um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grok-line" /></template>
