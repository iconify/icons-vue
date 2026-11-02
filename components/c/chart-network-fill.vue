<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzw_b9byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzw_b9byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-network-fill" /></template>
