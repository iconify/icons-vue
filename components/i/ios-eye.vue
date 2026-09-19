<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0g-o_bdg.css';
import '../../css/z/ztt_jxlej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i0g-o_bdg"/><path class="ztt_jxlej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-eye" /></template>
