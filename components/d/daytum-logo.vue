<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/ts9smeb3v.css';
import '../../css/v/v7x4ucb2s.css';
import '../../css/m/mg7qgd5-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ts9smeb3v"/><path class="v7x4ucb2s"/><path class="mg7qgd5-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:daytum-logo" /></template>
