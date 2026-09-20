<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz2y_fbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2y_fbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:game-fill" /></template>
