<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcwnmr0of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcwnmr0of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:box" /></template>
