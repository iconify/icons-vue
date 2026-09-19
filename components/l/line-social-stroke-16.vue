<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onsolsbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="onsolsbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-social-stroke-16" /></template>
