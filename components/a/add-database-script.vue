<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p376rq-oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p376rq-oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-database-script" /></template>
