<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuscgttwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuscgttwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bookmark-solid" /></template>
