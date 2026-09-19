<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvyy595xw.css';
import '../../css/t/t2k1y2acb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvyy595xw"/><path class="t2k1y2acb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-plus" /></template>
