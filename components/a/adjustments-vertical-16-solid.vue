<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9sia4b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w9sia4b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:adjustments-vertical-16-solid" /></template>
