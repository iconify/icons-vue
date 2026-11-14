<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zui1j9b_e.css';
import '../../css/x/x0tc4abcz.css';
import '../../css/w/w-jmn3bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zui1j9b_e"/><path class="x0tc4abcz"/><path class="w-jmn3bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-cable" /></template>
