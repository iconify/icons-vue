<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uli4gbhou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uli4gbhou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:magnet" /></template>
