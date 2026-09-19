<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhffs66ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zhffs66ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:angle-left" /></template>
