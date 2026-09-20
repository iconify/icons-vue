<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayvdx43dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ayvdx43dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:equipment-outline" /></template>
