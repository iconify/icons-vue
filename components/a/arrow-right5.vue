<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrr3flboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr3flboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right5" /></template>
