<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxctd4bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxctd4bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-ev-station" /></template>
