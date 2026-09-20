<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t95rl8bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t95rl8bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-robot-outline" /></template>
