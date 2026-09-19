<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yjxmw6bik.css';
import '../../css/t/t-5avtbey.css';
import '../../css/a/aswk6qohq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yjxmw6bik"/><path class="t-5avtbey"/><path class="aswk6qohq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:castle" /></template>
