<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab8x174bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab8x174bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:headphones-off" /></template>
