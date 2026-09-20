<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn5r_fhqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mn5r_fhqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:check-box" /></template>
