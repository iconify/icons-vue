<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohkm-6bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ohkm-6bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-a" /></template>
