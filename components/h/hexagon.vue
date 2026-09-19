<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xymg-f0_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xymg-f0_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hexagon" /></template>
