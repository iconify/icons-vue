<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uon7ubcpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uon7ubcpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-3-line" /></template>
