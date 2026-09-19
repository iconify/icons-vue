<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcpug3b7d.css';
import '../../css/o/oi41y_wwj.css';
import '../../css/r/rfmo84bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcpug3b7d"/><path class="oi41y_wwj"/><path class="rfmo84bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:chartdownwardstrend" /></template>
