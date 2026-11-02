<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1h0yxuds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1h0yxuds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-front-line" /></template>
