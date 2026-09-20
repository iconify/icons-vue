<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-ycvb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hj-ycvb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:convex-double-16" /></template>
