<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thf86pb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thf86pb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:frame-simple" /></template>
