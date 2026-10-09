<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtrypjbye.css';
import '../../css/d/dmyxypbyy.css';
import '../../css/b/bc7iv7cyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vtrypjbye"/><path class="dmyxypbyy"/><path class="bc7iv7cyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:demand-response-20-bold" /></template>
