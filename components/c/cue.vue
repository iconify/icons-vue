<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_zt233x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vz_zt233x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cue" /></template>
