<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzc9bummx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzc9bummx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dock-bottom" /></template>
