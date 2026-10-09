<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzc_ai_da.css';
import '../../css/l/l0bdr-bzi.css';
import '../../css/m/mkc2s70sv.css';
import '../../css/h/hqzf0_0is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yzc_ai_da"/><path class="l0bdr-bzi"/><path class="mkc2s70sv"/><path class="hqzf0_0is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contactless-20-bold" /></template>
