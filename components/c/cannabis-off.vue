<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjxz6jo1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjxz6jo1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cannabis-off" /></template>
