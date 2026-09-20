<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqxvfwbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqxvfwbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:flag" /></template>
