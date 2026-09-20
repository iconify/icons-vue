<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp5p-qjme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xp5p-qjme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-fill" /></template>
