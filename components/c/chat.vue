<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2-euybts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2-euybts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:chat" /></template>
