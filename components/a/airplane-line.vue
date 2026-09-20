<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz2g8fg_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz2g8fg_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airplane-line" /></template>
