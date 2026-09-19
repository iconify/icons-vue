<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhsfl6afw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mhsfl6afw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:less" /></template>
