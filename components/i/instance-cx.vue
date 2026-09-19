<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8kuy_ape.css';
import '../../css/z/z0z1a0aie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="c8kuy_ape"/><path class="z0z1a0aie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:instance-cx" /></template>
