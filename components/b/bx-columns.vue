<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wix1-6b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wix1-6b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-columns" /></template>
