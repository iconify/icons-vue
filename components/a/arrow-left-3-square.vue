<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv6irtb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv6irtb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-3-square" /></template>
