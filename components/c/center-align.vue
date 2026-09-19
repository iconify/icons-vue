<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxs59cbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxs59cbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:center-align" /></template>
