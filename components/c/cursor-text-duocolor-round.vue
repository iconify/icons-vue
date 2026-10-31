<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0yqracdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yqracdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-text-duocolor-round" /></template>
