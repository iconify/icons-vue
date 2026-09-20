<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kldnvggtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kldnvggtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:code-markup-12" /></template>
