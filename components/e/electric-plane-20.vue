<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u75ne53rx.css';
import '../../css/q/q0cgw-bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u75ne53rx"/><path class="q0cgw-bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-plane-20" /></template>
