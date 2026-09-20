<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk3yrs-uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="uk3yrs-uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple" /></template>
