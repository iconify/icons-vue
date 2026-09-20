<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drhd_vrgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="drhd_vrgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:carbon" /></template>
