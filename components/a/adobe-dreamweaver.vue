<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jevtp060j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jevtp060j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-dreamweaver" /></template>
