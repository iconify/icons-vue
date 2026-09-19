<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx81cc34q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx81cc34q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:headphones" /></template>
