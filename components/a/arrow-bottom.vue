<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqjow-hkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eqjow-hkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-bottom" /></template>
