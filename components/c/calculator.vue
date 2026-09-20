<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww_egybrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ww_egybrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:calculator" /></template>
