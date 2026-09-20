<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fexe7_bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fexe7_bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-knees-line" /></template>
