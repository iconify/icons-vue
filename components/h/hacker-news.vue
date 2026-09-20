<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brt9ow2dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brt9ow2dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hacker-news" /></template>
