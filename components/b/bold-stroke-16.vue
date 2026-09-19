<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx75f44uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx75f44uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bold-stroke-16" /></template>
