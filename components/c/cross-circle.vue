<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/o/obwkopbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="jtowsomii"><circle class="i2qezbnqp"/><path class="obwkopbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:cross-circle" /></template>
