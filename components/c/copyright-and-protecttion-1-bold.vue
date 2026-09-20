<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmdsdab3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmdsdab3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:copyright-and-protecttion-1-bold" /></template>
