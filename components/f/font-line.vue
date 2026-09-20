<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izm1r3bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izm1r3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-line" /></template>
