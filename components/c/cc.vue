<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/ki0xnbcvt.css';
import '../../css/m/md286fbip.css';
import '../../css/k/kn8bd-bng.css';
import '../../css/h/hx2tq71se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="ki0xnbcvt"/><g class="md286fbip"><path class="kn8bd-bng"/><path class="hx2tq71se"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:cc" /></template>
