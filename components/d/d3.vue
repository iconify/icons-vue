<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndzyi9kfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndzyi9kfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:d3" /></template>
