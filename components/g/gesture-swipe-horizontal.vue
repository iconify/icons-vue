<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pecsm4hfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pecsm4hfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe-horizontal" /></template>
