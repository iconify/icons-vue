<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz5_qkdfv.css';
import '../../css/m/mu_rg1b1t.css';
import '../../css/w/wpp7bqbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dz5_qkdfv"/><path class="mu_rg1b1t"/><path class="wpp7bqbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-water-20" /></template>
