<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk3vthbjv.css';
import '../../css/e/ewd4-9b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nk3vthbjv"/><circle class="ewd4-9b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:camera" /></template>
