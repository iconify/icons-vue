<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3fziz2vw.css';
import '../../css/x/xtkqegbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3fziz2vw"/><path class="xtkqegbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-combo-stacked" /></template>
