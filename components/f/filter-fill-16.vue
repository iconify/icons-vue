<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o815owbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o815owbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:filter-fill-16" /></template>
