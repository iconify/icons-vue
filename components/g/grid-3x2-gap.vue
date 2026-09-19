<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raz1blbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="raz1blbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:grid-3x2-gap" /></template>
