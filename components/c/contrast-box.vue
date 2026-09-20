<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f10q95yyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f10q95yyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contrast-box" /></template>
