<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2n6y2bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="g_2n6y2bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:day-light-wind" /></template>
