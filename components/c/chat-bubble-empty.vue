<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-pv84za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-pv84za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-empty" /></template>
