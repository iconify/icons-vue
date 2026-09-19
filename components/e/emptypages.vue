<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc10iubcv.css';
import '../../css/f/f6z-4gr0p.css';
import '../../css/d/dwhvop1-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc10iubcv"/><path class="f6z-4gr0p"/><path class="dwhvop1-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:emptypages" /></template>
