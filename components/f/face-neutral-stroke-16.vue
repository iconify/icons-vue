<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu8rf9bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wu8rf9bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-neutral-stroke-16" /></template>
