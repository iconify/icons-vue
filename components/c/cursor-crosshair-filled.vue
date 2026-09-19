<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6xz549ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6xz549ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-crosshair-filled" /></template>
