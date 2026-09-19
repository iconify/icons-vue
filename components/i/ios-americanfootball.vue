<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4zrtacay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4zrtacay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-americanfootball" /></template>
