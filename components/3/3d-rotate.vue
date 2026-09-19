<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mhks76b_b.css';
import '../../css/g/gcvor9ish.css';
import '../../css/k/ke-lvtb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="mhks76b_b"/><path class="gcvor9ish"/><path class="ke-lvtb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:3d-rotate" /></template>
