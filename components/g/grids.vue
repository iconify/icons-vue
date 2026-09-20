<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnit63bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnit63bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:grids" /></template>
