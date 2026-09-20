<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8vs9blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq8vs9blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bath" /></template>
