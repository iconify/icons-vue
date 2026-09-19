<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl4-n0bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zl4-n0bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:blockchain" /></template>
