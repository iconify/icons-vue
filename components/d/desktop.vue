<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gni1zbbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gni1zbbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:desktop" /></template>
