<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3-yu6bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u3-yu6bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:book" /></template>
