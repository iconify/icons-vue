<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psh4icc1n.css';
import '../../css/u/uo6pjzbsg.css';
import '../../css/o/ozo3l73pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="psh4icc1n"/><path class="uo6pjzbsg"/><path class="ozo3l73pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:auto-scroll" /></template>
