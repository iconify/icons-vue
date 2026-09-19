<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xds1_qbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xds1_qbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-right-circle-fill" /></template>
