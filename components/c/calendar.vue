<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi1gnzbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xi1gnzbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:calendar" /></template>
