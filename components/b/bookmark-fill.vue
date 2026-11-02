<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz6xh3ccq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz6xh3ccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-fill" /></template>
