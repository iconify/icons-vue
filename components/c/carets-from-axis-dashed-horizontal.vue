<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaic6sbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaic6sbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-from-axis-dashed-horizontal" /></template>
