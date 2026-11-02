<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgbl1b5my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cgbl1b5my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-down-16-solid" /></template>
