<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orha0ukvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="orha0ukvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:italic-s" /></template>
