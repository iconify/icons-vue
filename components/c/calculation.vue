<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_hnjcrah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l_hnjcrah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calculation" /></template>
