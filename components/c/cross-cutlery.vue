<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4byx8bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t4byx8bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cross-cutlery" /></template>
