<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysul9tm-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ysul9tm-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-out-fill-16" /></template>
