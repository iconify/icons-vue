<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo-wa019m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eo-wa019m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrows" /></template>
