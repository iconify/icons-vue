<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghtige71w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ghtige71w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:fast-forward" /></template>
