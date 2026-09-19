<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do0n5ibbt.css';
import '../../css/n/nnksa96uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do0n5ibbt"/><path class="nnksa96uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-spa" /></template>
