<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx8sjhbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx8sjhbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-left" /></template>
