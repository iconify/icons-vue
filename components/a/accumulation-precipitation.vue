<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq18vxb1u.css';
import '../../css/g/g7j88-bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uq18vxb1u"/><path class="g7j88-bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accumulation-precipitation" /></template>
