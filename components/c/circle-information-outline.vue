<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhzasm3by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fhzasm3by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-information-outline" /></template>
