<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfzvm7b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfzvm7b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:carousel-horizontal" /></template>
