<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi331ob7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vi331ob7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:home" /></template>
