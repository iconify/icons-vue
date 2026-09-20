<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fr_tmn9fp.css';
import '../../css/j/jot55yhti.css';
import '../../css/x/x4pob2bni.css';
import '../../css/b/bcpsrtbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="fr_tmn9fp"/><path class="jot55yhti"/><path class="x4pob2bni"/><path class="bcpsrtbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-minimalistic-linear" /></template>
