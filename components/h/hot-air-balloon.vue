<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jx6yqbbhl.css';
import '../../css/s/smmxe_bdk.css';
import '../../css/h/hfshdjlhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jx6yqbbhl"/><path class="smmxe_bdk"/><path class="hfshdjlhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hot-air-balloon" /></template>
