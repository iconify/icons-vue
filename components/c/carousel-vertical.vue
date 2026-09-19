<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nob9nfb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nob9nfb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:carousel-vertical" /></template>
