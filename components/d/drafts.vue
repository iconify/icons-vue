<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k-79yg7vl.css';
import '../../css/h/hjux57bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path clip-rule="evenodd" class="k-79yg7vl"/><path vector-effect="non-scaling-stroke" class="hjux57bau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:drafts" /></template>
