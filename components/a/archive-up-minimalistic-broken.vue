<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p5qbbdc2d.css';
import '../../css/v/vmvmzcbhp.css';
import '../../css/e/e1dpahbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p5qbbdc2d"/><path class="vmvmzcbhp"/><path class="e1dpahbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-minimalistic-broken" /></template>
