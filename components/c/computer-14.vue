<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufcva7b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ufcva7b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:computer-14" /></template>
