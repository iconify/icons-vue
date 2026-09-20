<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/ecjyiacqx.css';
import '../../css/i/i8r_mr_be.css';
import '../../css/x/x-fkqvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><rect class="ecjyiacqx"/><rect class="i8r_mr_be"/><path class="x-fkqvbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:headphones-fill" /></template>
