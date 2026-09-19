<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3wuxibxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3wuxibxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-credit-card" /></template>
