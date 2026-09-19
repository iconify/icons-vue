<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js53_-1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js53_-1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-border-bottom" /></template>
