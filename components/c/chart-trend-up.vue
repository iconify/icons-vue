<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l15517bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l15517bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-trend-up" /></template>
