<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8-zfaccj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8-zfaccj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:home-alt-slim" /></template>
