<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plx5kkbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plx5kkbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-line" /></template>
