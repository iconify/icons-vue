<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d98mzkk1w.css';
import '../../css/t/t9o16wbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d98mzkk1w"/><path class="t9o16wbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:deaf" /></template>
