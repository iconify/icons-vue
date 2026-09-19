<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb0sabbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0sabbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sort-z-a" /></template>
