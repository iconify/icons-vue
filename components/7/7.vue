<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxtu_6byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cxtu_6byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:7" /></template>
