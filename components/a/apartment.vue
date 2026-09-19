<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph994hqiv.css';
import '../../css/f/fcg7ob6nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph994hqiv"/><path class="fcg7ob6nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:apartment" /></template>
