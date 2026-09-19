<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m20u9ob6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m20u9ob6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:css3-alt" /></template>
