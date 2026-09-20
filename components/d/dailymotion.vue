<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i23ml48ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i23ml48ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dailymotion" /></template>
