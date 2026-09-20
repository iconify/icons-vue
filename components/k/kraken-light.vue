<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oelcicc3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":150.5,"height":25.6};
const content = `<path class="oelcicc3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kraken-light" /></template>
