<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dktlm67gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dktlm67gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-from-axis-vertical" /></template>
