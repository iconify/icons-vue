<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yba2_offd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yba2_offd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:heart-solid" /></template>
