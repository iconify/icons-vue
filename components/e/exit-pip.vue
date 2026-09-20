<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71pcf2_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w71pcf2_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:exit-pip" /></template>
