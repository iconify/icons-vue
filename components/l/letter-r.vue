<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0zbf7bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0zbf7bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-r" /></template>
