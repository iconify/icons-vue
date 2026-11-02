<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmnkyxb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmnkyxb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-gemini-line" /></template>
