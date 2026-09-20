<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg1poxbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg1poxbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-2-line" /></template>
