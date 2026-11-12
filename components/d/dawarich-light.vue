<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdtzqfxwt.css';
import '../../css/t/tx9vi1y_m.css';
import '../../css/t/tr7cg_bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdtzqfxwt"/><path class="tx9vi1y_m"/><path class="tr7cg_bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dawarich-light" /></template>
