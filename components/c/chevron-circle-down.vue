<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imt9l1hvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="imt9l1hvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chevron-circle-down" /></template>
