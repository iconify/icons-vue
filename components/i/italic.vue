<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9cn8b7_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n9cn8b7_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:italic" /></template>
