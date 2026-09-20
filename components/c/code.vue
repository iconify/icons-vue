<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpm55bzfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpm55bzfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:code" /></template>
