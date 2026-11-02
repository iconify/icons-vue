<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p96xxynhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p96xxynhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-3-line" /></template>
