<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk-i_ibgn.css';
import '../../css/y/ykc7uz8oe.css';
import '../../css/z/z17_xq-jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pk-i_ibgn"/><path class="ykc7uz8oe"/><path class="z17_xq-jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-median" /></template>
