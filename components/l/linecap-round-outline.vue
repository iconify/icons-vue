<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdrdz7b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fdrdz7b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linecap-round-outline" /></template>
