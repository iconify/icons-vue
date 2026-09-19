<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmva9bc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmva9bc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:evil2" /></template>
