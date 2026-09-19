<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo7uac-kj.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wo7uac-kj"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-bar-floating" /></template>
