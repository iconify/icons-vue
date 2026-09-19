<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev1fg5bdw.css';
import '../../css/j/j8_u0x2hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ev1fg5bdw"/><path class="j8_u0x2hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:crop-outline" /></template>
