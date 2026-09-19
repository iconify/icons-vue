<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjk-i_bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjk-i_bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-checkbox-minus" /></template>
