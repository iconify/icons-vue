<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uopsl9spe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uopsl9spe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-left-square-fill" /></template>
