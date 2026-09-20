<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3-ko4bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3-ko4bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:expand-player-fill" /></template>
