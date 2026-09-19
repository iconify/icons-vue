<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt8jb-7jt.css';
import '../../css/v/v3_7cbqjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="yt8jb-7jt"/><path class="v3_7cbqjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hole-filling" /></template>
