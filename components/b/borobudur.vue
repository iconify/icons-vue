<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahi4ik3zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahi4ik3zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:borobudur" /></template>
