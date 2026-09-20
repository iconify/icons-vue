<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwq_k-uvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fwq_k-uvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-historic" /></template>
