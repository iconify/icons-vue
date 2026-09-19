<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgm17v0ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgm17v0ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gas" /></template>
