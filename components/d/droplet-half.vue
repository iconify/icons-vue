<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q91u8jbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q91u8jbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:droplet-half" /></template>
