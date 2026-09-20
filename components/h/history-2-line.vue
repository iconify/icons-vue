<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg7dkbyqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg7dkbyqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-2-line" /></template>
