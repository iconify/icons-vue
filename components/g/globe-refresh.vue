<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3p5udwiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3p5udwiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-refresh" /></template>
