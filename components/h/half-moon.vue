<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqaj9fbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqaj9fbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:half-moon" /></template>
