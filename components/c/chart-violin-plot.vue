<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgpzimtyu.css';
import '../../css/b/b3jg8vbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><path class="b3jg8vbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-violin-plot" /></template>
