<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pzxv190ut.css';
import '../../css/x/xuz284bnw.css';
import '../../css/r/rysm2pqae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pzxv190ut"/><circle class="xuz284bnw"/><path class="rysm2pqae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:id-verified" /></template>
