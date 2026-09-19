<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpxwy_jwh.css';
import '../../css/k/kqmlytbco.css';
import '../../css/m/mw99uy5ni.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wpxwy_jwh"/><path class="kqmlytbco"/><path class="mw99uy5ni"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-network-automation" /></template>
