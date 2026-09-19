<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/oobb8_b6g.css';
import '../../css/n/nqog7vbel.css';
import '../../css/x/xomb33bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="oobb8_b6g"/><path class="nqog7vbel"/><path class="xomb33bku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:customize" /></template>
