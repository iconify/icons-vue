<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg_k29_bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yg_k29_bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eyedropper-halffull" /></template>
