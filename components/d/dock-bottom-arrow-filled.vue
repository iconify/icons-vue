<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvl56vbvg.css';
import '../../css/t/tnzkiacoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvl56vbvg"/><path class="tnzkiacoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-arrow-filled" /></template>
