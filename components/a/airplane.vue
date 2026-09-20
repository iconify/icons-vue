<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzr89gbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wzr89gbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:airplane" /></template>
