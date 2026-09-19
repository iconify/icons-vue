<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlzy1_b2o.css';
import '../../css/h/hv0axw6am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tlzy1_b2o"/><path class="hv0axw6am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-fill-16" /></template>
