<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys_8zbbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys_8zbbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:home-heart" /></template>
