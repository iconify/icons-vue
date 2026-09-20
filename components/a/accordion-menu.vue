<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xstc6fbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xstc6fbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:accordion-menu" /></template>
