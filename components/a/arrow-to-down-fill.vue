<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o05y2fgyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o05y2fgyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-to-down-fill" /></template>
