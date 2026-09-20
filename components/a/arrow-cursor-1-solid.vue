<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk9bt3b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk9bt3b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-cursor-1-solid" /></template>
