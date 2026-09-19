<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jkf_3mbfp.css';
import '../../css/t/tvnbxhb2o.css';
import '../../css/h/hb-wj9-hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jkf_3mbfp"/><path class="tvnbxhb2o"/><path class="hb-wj9-hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:blockchain-06" /></template>
