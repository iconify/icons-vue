<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn72ziboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn72ziboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chess-line" /></template>
