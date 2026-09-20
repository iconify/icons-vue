<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/a/arwbrbczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="jtowsomii"><circle class="i2qezbnqp"/><path class="arwbrbczk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:chevron-up-circle" /></template>
