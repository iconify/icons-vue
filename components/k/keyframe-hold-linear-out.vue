<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q64m484xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q64m484xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-linear-out" /></template>
