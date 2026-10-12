<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1fi5_bhd.css';
import '../../css/p/p7vazbcay.css';
import '../../css/d/dgu6khf1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u1fi5_bhd"/><path class="p7vazbcay"/><path class="dgu6khf1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-engine-20-bold" /></template>
