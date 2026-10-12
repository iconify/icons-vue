<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2d6budho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":843.89,"height":843.9};
const content = `<path class="n2d6budho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eggerco" /></template>
