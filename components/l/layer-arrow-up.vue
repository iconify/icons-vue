<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa9qyt-lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa9qyt-lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layer-arrow-up" /></template>
