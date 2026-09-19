<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u30ldabiv.css';
import '../../css/m/mydhkgbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u30ldabiv"/><path class="mydhkgbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:casino" /></template>
