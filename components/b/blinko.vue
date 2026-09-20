<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1rs_hvhx.css';
import '../../css/z/zsi22_bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1rs_hvhx"/><path class="zsi22_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko" /></template>
