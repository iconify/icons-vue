<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-o7h.css';
import '../../css/s/s8h7-c.css';
import '../../css/n/n0_dif.css';
import '../../css/s/s6vdjj.css';
import '../../css/h/h3davo.css';
import '../../css/c/c4x52o.css';
import '../../css/m/mtr4or.css';
import '../../css/s/so-from-28.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-o7h s8h7-c"/><path class="n0_dif qa-o7h"/><path class="qa-o7h s6vdjj"/><path class="h3davo qa-o7h"/><path class="c4x52o qa-o7h"/><path class="mtr4or qa-o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:list-3" /></template>
