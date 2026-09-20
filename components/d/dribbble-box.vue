<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp17d_muq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp17d_muq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dribbble-box" /></template>
