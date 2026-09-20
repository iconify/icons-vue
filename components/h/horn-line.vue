<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzxol0-lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzxol0-lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:horn-line" /></template>
