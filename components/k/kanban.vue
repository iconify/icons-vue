<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjhe4x-cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjhe4x-cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:kanban" /></template>
