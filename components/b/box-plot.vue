<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w62ry_euj.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w62ry_euj"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:box-plot" /></template>
