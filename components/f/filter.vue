<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eht0_oe3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="eht0_oe3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:filter" /></template>
