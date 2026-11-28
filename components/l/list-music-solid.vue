<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlem3eb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlem3eb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-music-solid" /></template>
