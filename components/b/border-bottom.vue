<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw16btbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dw16btbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:border-bottom" /></template>
