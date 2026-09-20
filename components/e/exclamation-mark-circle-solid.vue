<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7sif6b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z7sif6b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:exclamation-mark-circle-solid" /></template>
