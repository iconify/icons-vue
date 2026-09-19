<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehy36_bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehy36_bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:fi" /></template>
