<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5kdsjbsk.css';
import '../../css/w/wl2vi-wfs.css';
import '../../css/p/ph-mjcb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="u5kdsjbsk"/><path class="wl2vi-wfs"/><path class="ph-mjcb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-rectangle" /></template>
