<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd_rk-b_e.css';
import '../../css/g/ggn80i4hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hd_rk-b_e"/><path class="ggn80i4hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:link" /></template>
