<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncsdce20j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ncsdce20j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calculator" /></template>
