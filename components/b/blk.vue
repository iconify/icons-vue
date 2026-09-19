<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hxe6apb_t.css';
import '../../css/a/adiuw0bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="hxe6apb_t"/><path class="adiuw0bdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:blk" /></template>
