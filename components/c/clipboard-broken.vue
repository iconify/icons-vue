<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ndq0ugbyy.css';
import '../../css/q/qu0eyjbrg.css';
import '../../css/m/m390b8qby.css';
import '../../css/r/ruv56nblh.css';
import '../../css/r/r_va8z9vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ndq0ugbyy"/><path class="qu0eyjbrg"/><path class="m390b8qby"/><path class="ruv56nblh"/><path class="r_va8z9vn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-broken" /></template>
