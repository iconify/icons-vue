<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unp-q8byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unp-q8byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:greenhouse" /></template>
