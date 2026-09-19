<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ift36sbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ift36sbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-map" /></template>
