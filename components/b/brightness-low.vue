<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed6yhd3rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ed6yhd3rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-low" /></template>
