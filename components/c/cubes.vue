<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkzyu1bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkzyu1bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cubes" /></template>
