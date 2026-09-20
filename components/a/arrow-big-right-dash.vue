<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhptluobe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhptluobe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-right-dash" /></template>
