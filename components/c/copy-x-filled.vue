<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuforsmvs.css';
import '../../css/r/r_3yuac4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuforsmvs"/><path class="r_3yuac4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copy-x-filled" /></template>
