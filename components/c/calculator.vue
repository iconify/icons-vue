<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ws9_odf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c1ws9_odf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:calculator" /></template>
