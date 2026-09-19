<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t114_gb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t114_gb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chart-bar" /></template>
