<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxq44iahj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxq44iahj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bookmark-plus" /></template>
