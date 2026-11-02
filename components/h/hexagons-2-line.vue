<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qblh994vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qblh994vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hexagons-2-line" /></template>
