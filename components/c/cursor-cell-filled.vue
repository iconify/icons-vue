<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isnxa6b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isnxa6b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-cell-filled" /></template>
