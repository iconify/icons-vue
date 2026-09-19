<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7c0-q0sw.css';
import '../../css/s/sgg5g4blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7c0-q0sw"/><path class="sgg5g4blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beach-filled" /></template>
