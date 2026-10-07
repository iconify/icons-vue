<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngg5mbc4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngg5mbc4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gps" /></template>
