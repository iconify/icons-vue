<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhb-53bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":114,"height":46};
const content = `<path class="fhb-53bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:arc-dark" /></template>
