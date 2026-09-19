<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_lxpz16r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_lxpz16r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-pinterest" /></template>
