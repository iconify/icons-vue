<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwubsq7mq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwubsq7mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fork-spoon-line" /></template>
