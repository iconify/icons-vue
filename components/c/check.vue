<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzr8kacbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pzr8kacbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:check" /></template>
