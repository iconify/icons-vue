<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_lny9fez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_lny9fez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-coupon" /></template>
