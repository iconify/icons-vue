<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/skui-0bnl.css';
import '../../css/m/m97iezbay.css';
import '../../css/m/mjojrgq4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="skui-0bnl"/><path class="m97iezbay"/><path class="mjojrgq4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-broken" /></template>
