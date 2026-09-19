<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5exsidjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y5exsidjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-3x3-stroke-12" /></template>
