<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbnco8jkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnco8jkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-up" /></template>
