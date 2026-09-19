<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnj__kbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b cnj__kbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cube-inside-filled" /></template>
