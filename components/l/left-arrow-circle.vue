<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu7mpeebk.css';
import '../../css/n/npp4pnb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7mpeebk"/><path class="npp4pnb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:left-arrow-circle" /></template>
