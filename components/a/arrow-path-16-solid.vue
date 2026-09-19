<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvv8xvb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rvv8xvb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-16-solid" /></template>
