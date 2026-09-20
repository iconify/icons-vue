<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iuhehmbsp.css';
import '../../css/z/zxhjaubkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 1)" class="bi12bsetm"><path class="iuhehmbsp"/><circle class="zxhjaubkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:lock" /></template>
