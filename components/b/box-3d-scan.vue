<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gwnx6_byv.css';
import '../../css/p/phg74re_f.css';
import '../../css/g/g6ys_sbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gwnx6_byv"/><path class="phg74re_f"/><path class="g6ys_sbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-scan" /></template>
