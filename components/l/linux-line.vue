<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1tm3acmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1tm3acmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:linux-line" /></template>
