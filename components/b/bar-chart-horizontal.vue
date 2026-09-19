<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbxo19bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbxo19bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bar-chart-horizontal" /></template>
