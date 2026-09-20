<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww19cizxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ww19cizxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-down-dashed-square" /></template>
