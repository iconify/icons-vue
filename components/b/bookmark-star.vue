<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsq26gb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsq26gb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bookmark-star" /></template>
