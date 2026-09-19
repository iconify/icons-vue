<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfiw6xiub.css';
import '../../css/m/mfnnmcbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfiw6xiub"/><path class="mfnnmcbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:condition-point" /></template>
