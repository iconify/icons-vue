<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2nnolgnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2nnolgnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:emberdotjs" /></template>
