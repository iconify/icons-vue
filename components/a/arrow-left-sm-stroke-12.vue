<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrtymebab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rrtymebab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-sm-stroke-12" /></template>
