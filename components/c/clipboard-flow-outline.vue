<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbf406y8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbf406y8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-flow-outline" /></template>
