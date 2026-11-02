<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdf2hi5sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdf2hi5sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contrast-line" /></template>
