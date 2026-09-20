<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia59wicrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ia59wicrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:laminas" /></template>
