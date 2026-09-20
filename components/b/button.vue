<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03gou64b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s03gou64b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:button" /></template>
