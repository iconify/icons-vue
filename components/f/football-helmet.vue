<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etcjt1s5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etcjt1s5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:football-helmet" /></template>
