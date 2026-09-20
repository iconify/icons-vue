<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjrs50btb.css';
import '../../css/c/cig9b4c-v.css';
import '../../css/z/zp7f7h2us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mjrs50btb"/><path class="cig9b4c-v"/><path class="zp7f7h2us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-barber-light-sign" /></template>
