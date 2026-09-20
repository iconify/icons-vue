<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj79lzb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj79lzb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:curling" /></template>
