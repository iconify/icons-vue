<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y_4vp8bgj.css';
import '../../css/n/nr2f0pbpu.css';
import '../../css/e/esvv2bcpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y_4vp8bgj"/><path class="nr2f0pbpu"/><path class="esvv2bcpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bed-single-02" /></template>
