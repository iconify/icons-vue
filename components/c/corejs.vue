<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4lt0ubcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l4lt0ubcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:corejs" /></template>
