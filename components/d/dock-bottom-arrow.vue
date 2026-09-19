<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3-glbdq.css';
import '../../css/t/tnzkiacoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3-glbdq"/><path class="tnzkiacoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-arrow" /></template>
