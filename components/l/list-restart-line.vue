<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7zolnbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7zolnbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-restart-line" /></template>
