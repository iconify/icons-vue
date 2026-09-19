<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqyn79ggl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqyn79ggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bone" /></template>
