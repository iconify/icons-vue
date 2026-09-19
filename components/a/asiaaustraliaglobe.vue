<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4dm09b_v.css';
import '../../css/s/scg0arb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4dm09b_v"/><path class="scg0arb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:asiaaustraliaglobe" /></template>
