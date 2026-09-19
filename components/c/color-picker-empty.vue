<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjykl1blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjykl1blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:color-picker-empty" /></template>
