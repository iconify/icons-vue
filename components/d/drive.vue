<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrb8x1bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hrb8x1bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:drive" /></template>
