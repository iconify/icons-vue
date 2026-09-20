<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwc4rkb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwc4rkb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:elastic-stack" /></template>
