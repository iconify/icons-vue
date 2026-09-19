<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpsjndblj.css';
import '../../css/i/igk3ecc7a.css';
import '../../css/i/ihjfc8h8i.css';
import '../../css/d/doqds4bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpsjndblj"/><path class="igk3ecc7a"/><path class="ihjfc8h8i"/><path class="doqds4bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lastquartermoon" /></template>
