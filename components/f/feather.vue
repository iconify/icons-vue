<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3-tgj1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yp3-tgj1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:feather" /></template>
