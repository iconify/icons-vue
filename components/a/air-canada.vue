<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sumq48c7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sumq48c7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:air-canada" /></template>
