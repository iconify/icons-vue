<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcsztvbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcsztvbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:languagetool" /></template>
