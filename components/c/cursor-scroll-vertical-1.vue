<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvs623brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvs623brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-scroll-vertical-1" /></template>
