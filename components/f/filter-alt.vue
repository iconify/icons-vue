<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muvjibw6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muvjibw6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:filter-alt" /></template>
