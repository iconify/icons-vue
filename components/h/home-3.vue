<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aucwa7bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aucwa7bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:home-3" /></template>
