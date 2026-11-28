<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8x5w1b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8x5w1b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-filter-duo" /></template>
