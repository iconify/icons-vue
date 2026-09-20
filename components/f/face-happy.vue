<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-72742ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-72742ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:face-happy" /></template>
