<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7d34ou2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7d34ou2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-header" /></template>
