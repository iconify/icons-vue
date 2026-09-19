<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypaq_fbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypaq_fbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:file-not-found" /></template>
