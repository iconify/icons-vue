<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxvmtd8dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xxvmtd8dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:coursera-square" /></template>
