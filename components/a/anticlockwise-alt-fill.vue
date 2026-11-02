<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx_9pkbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx_9pkbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-alt-fill" /></template>
