<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-lmtub9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d-lmtub9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-down-stroke-12" /></template>
