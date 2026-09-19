<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0wa4skuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a0wa4skuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:grin" /></template>
