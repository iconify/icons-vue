<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqtyr2w2k.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qqtyr2w2k"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-error-bar-alt" /></template>
