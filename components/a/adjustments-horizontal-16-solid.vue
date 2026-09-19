<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-vnx3bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-vnx3bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:adjustments-horizontal-16-solid" /></template>
