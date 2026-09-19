<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgx52e-ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fgx52e-ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-high" /></template>
