<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdtm8jb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qdtm8jb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:clock-face" /></template>
