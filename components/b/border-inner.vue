<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xybm8_bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xybm8_bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-inner" /></template>
