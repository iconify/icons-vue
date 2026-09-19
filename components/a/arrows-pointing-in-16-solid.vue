<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3x3y2w-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z3x3y2w-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-pointing-in-16-solid" /></template>
