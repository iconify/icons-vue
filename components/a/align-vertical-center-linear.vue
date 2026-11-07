<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aed5lhbuz.css';
import '../../css/j/jttm9ch_g.css';
import '../../css/a/avlf34b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aed5lhbuz"/><path class="jttm9ch_g"/><path class="avlf34b0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-center-linear" /></template>
