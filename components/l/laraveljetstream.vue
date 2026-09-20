<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav5dg_xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jav5dg_xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:laraveljetstream" /></template>
