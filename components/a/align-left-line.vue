<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjogw_dsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjogw_dsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-left-line" /></template>
