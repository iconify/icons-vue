<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lta8hozjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lta8hozjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-right-line" /></template>
