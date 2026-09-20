<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zt0gceb0n.css';
import '../../css/w/w5-8w2bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><circle class="zt0gceb0n"/><path class="w5-8w2bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:circle-menu" /></template>
