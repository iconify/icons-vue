<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxikenb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxikenb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-gemini-fill" /></template>
