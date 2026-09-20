<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozerakbgv.css';
import '../../css/g/glfvv6bkn.css';
import '../../css/g/gfjgj5bsy.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/p/pe6ae7qfy.css';
import '../../css/z/zis3p-m8u.css';
import '../../css/s/squ0yg8xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ozerakbgv"/><path class="glfvv6bkn"/><path class="gfjgj5bsy"/><g class="brzn_0bpr"><path class="pe6ae7qfy"/><path class="zis3p-m8u"/><path class="squ0yg8xb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bow-and-arrow" /></template>
