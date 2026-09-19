<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_j66ccof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_j66ccof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-linear-in-filled" /></template>
