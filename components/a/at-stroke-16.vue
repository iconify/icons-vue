<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwgw36hjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bwgw36hjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:at-stroke-16" /></template>
