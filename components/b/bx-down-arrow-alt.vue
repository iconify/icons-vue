<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtxym15qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxym15qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-down-arrow-alt" /></template>
