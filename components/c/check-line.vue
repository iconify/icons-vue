<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmi_rmt5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmi_rmt5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:check-line" /></template>
