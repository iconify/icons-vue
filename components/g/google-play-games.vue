<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8jgw_rfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8jgw_rfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-play-games" /></template>
