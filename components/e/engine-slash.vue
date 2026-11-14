<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/liypecb8n.css';
import '../../css/i/inawvkb3j.css';
import '../../css/p/pmgxj2bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="liypecb8n"/><path class="inawvkb3j"/><path class="pmgxj2bto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:engine-slash" /></template>
