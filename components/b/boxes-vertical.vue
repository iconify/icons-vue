<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa-00nb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wa-00nb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:boxes-vertical" /></template>
