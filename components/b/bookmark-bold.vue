<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv3wqwbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv3wqwbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark-bold" /></template>
