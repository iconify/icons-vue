<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cqlnbtbkx.css';
import '../../css/m/mp_70hbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cqlnbtbkx"/><path clip-rule="evenodd" class="mp_70hbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-2-bold" /></template>
