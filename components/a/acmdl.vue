<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot1lbzb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ot1lbzb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:acmdl" /></template>
