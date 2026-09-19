<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdhl94coo.css';
import '../../css/l/lzvsylpnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tdhl94coo"/><path class="lzvsylpnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:identification" /></template>
