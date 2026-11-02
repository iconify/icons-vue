<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i62i4obqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i62i4obqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-angle-fill" /></template>
