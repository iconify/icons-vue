<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt384zkpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt384zkpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-check" /></template>
