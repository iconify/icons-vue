<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/da4x8hbcl.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/m/mzgzwghgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="da4x8hbcl"/><circle class="aqhok2bbj"/><path class="mzgzwghgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:e-mail-light" /></template>
