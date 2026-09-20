<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qgctxwzlr.css';
import '../../css/o/ows_o8gdi.css';
import '../../css/q/qliqwmf6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="qgctxwzlr"/><circle class="ows_o8gdi"/><circle class="qliqwmf6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bubble" /></template>
