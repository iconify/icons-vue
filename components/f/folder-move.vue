<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-6p2220y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-6p2220y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-move" /></template>
