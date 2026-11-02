<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swy716zau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swy716zau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-line" /></template>
