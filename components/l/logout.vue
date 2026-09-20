<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qv4ebs0bg.css';
import '../../css/h/h1lupabnl.css';
import '../../css/h/hgoqu4bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qv4ebs0bg"/><path class="h1lupabnl"/><path class="hgoqu4bte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:logout" /></template>
