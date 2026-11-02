<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td06nob6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td06nob6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firework-line" /></template>
