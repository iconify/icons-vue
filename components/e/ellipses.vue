<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syoe0rb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="syoe0rb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:ellipses" /></template>
