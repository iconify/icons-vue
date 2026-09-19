<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_we1sb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_we1sb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-3-square-thin" /></template>
