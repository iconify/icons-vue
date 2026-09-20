<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/inq2hh19w.css';
import '../../css/q/qyhjd8bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":74,"height":74};
const content = `<g class="ft5dv1b6b"><path class="inq2hh19w"/><path class="qyhjd8bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:heroui-light" /></template>
