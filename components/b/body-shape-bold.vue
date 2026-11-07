<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf4ca1btm.css';
import '../../css/x/xa-1wqb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4ca1btm"/><path class="xa-1wqb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-bold" /></template>
