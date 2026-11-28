<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwp0bm6lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwp0bm6lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-play" /></template>
