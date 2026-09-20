<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly2d8dboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly2d8dboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-double-up" /></template>
