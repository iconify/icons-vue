<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz9iv6bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz9iv6bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-right" /></template>
