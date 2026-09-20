<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/a/a0a7pbcab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 2)" class="jtowsomii"><circle class="i2qezbnqp"/><path class="a0a7pbcab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-left-circle" /></template>
