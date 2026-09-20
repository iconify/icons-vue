<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o00hksstx.css';
import '../../css/a/a_r59m-6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o00hksstx"/><path class="a_r59m-6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-volume-high" /></template>
