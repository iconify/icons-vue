<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_t41-uxm.css';
import '../../css/q/qpkn_bweo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g_t41-uxm"/><path class="qpkn_bweo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-shader" /></template>
