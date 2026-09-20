<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmo_l8brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmo_l8brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adventofcode" /></template>
