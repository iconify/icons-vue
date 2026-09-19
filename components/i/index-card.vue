<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9dxxwbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z9dxxwbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:index-card" /></template>
