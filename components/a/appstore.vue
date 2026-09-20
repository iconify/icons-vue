<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-ub77t1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-ub77t1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:appstore" /></template>
