<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrt9xcbpr.css';
import '../../css/x/xtmnjwu4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="wrt9xcbpr"/><path class="xtmnjwu4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:card-view-large-filled" /></template>
