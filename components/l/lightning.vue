<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llc-1mbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="llc-1mbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:lightning" /></template>
