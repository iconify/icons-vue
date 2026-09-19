<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua1k4no5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1k4no5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-swap" /></template>
