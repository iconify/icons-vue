<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1lsc9bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1lsc9bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:armkeil" /></template>
