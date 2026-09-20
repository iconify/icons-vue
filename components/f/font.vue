<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e59f65b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e59f65b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:font" /></template>
