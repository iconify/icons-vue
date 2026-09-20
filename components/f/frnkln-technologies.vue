<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfagilzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":321,"height":294};
const content = `<path class="vvfagilzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:frnkln-technologies" /></template>
