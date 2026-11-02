<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mawy-2kwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mawy-2kwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-2-fill" /></template>
