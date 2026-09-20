<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnpz_eeaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wnpz_eeaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:circle-solid" /></template>
