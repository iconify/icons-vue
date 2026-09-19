<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/ncueohb1u.css';
import '../../css/g/gganp7bnf.css';
import '../../css/t/t0brvj_8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ncueohb1u"/><path class="gganp7bnf"/><path class="t0brvj_8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-wallet" /></template>
