<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe3j86vbb.css';
import '../../css/i/i8b66go_s.css';
import '../../css/v/vrmdo4bib.css';
import '../../css/i/i771m-bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe3j86vbb"/><path class="i8b66go_s"/><path class="vrmdo4bib"/><path class="i771m-bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:line-spacing" /></template>
