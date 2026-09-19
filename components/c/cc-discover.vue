<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9ieug-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yy9ieug-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-discover" /></template>
