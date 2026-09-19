<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0tegibop.css';
import '../../css/l/ln3y43bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0tegibop"/><path class="ln3y43bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:av-timer" /></template>
