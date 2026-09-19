<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp36jldus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp36jldus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-up" /></template>
