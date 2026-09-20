<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnow--1ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bnow--1ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:browserstack" /></template>
