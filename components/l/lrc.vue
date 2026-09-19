<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmbggnbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pmbggnbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lrc" /></template>
