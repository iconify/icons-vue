<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v4tjwzr-k.css';
import '../../css/k/ktpncgb0v.css';
import '../../css/w/wy63pibnm.css';
import '../../css/e/ehgcfqbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v4tjwzr-k"/><path class="ktpncgb0v"/><path class="wy63pibnm"/><path class="ehgcfqbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-broken" /></template>
