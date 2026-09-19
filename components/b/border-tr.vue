<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulu__1bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulu__1bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-tr" /></template>
