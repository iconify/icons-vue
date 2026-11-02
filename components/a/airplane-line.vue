<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbs6kdlzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbs6kdlzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airplane-line" /></template>
