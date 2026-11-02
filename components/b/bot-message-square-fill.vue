<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m09lz5b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m09lz5b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bot-message-square-fill" /></template>
