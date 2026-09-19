<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_hr98mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p0_hr98mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-sm-fill-12" /></template>
