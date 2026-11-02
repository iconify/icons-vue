<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-5n0kbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y-5n0kbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-left-16-solid" /></template>
