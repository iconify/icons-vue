<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv_nh4bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uv_nh4bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calculator-alt" /></template>
