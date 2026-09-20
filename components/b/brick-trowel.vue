<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxeklnbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zxeklnbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:brick-trowel" /></template>
