<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mogbiy72d.css';
import '../../css/y/yyolqcc_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mogbiy72d"/><path class="yyolqcc_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-protected" /></template>
