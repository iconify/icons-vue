<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fka5i5bun.css';
import '../../css/w/wfbp_rb6j.css';
import '../../css/e/ew1brccxv.css';
import '../../css/n/nk2ku8bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":290,"height":85};
const content = `<path class="fka5i5bun"/><path class="wfbp_rb6j"/><path class="ew1brccxv"/><path class="nk2ku8bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ben-and-jerrys" /></template>
