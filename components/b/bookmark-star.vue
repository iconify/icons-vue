<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ch7qbai.css';
import '../../css/u/u7ok3ntpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ch7qbai"/><path class="u7ok3ntpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bookmark-star" /></template>
