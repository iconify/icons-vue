<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3zwszm_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l3zwszm_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:layout-split" /></template>
