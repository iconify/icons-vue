<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ex8kgyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ex8kgyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cannabis-leaf" /></template>
