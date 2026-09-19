<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2g63cekk.css';
import '../../css/h/hm4-mmydo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2g63cekk"/><path class="hm4-mmydo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-dailymotion" /></template>
