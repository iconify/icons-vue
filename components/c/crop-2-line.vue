<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2h8fgbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2h8fgbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crop-2-line" /></template>
