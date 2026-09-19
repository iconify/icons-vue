<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw-fxp2ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="bw-fxp2ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:forrst" /></template>
