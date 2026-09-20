<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvj0xrezm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvj0xrezm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dashboard-gauge-1-remix" /></template>
