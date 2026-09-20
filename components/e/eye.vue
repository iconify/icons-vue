<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95mjtb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f95mjtb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:eye" /></template>
