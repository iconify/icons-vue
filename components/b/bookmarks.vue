<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idw-rxyaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="idw-rxyaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:bookmarks" /></template>
