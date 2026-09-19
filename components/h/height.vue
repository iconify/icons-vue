<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub9y_mh9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub9y_mh9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:height" /></template>
