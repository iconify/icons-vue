<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f9_wrwbrn.css';
import '../../css/l/lfcen-bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 5)" class="bi12bsetm"><path class="f9_wrwbrn"/><circle class="lfcen-bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:iphone-landscape" /></template>
