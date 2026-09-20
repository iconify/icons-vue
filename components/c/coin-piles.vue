<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cedsxbbuw.css';
import '../../css/v/vvu8i0bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cedsxbbuw"/><path class="vvu8i0bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:coin-piles" /></template>
