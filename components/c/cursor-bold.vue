<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1aasd4zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1aasd4zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cursor-bold" /></template>
