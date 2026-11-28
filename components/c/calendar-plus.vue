<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/manu--2ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="manu--2ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-plus" /></template>
