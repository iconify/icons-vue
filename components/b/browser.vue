<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yel91y_cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yel91y_cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:browser" /></template>
