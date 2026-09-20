<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk6mrwbwh.css';
import '../../css/e/ehn9ppzlr.css';
import '../../css/j/jpbcbrl-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tk6mrwbwh"/><path class="ehn9ppzlr"/><path class="jpbcbrl-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:livescript" /></template>
