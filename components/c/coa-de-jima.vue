<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxhtexb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxhtexb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coa-de-jima" /></template>
