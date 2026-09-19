<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo8f6ub5d.css';
import '../../css/i/ibm4w8blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8f6ub5d"/><path class="ibm4w8blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bomb" /></template>
