<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-5209bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-5209bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lungs-fill" /></template>
