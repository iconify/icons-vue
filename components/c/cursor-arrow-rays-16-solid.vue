<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra2ozbcib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ra2ozbcib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cursor-arrow-rays-16-solid" /></template>
