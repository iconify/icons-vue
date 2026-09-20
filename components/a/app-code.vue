<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek537ccbf.css';
import '../../css/f/fgut1gbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ek537ccbf"/><path class="fgut1gbfe ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-code" /></template>
