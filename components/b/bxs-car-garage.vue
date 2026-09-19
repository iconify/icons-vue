<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef1_z1bld.css';
import '../../css/h/h0_g0cb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef1_z1bld"/><path class="h0_g0cb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-car-garage" /></template>
