<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cql1pwtbp.css';
import '../../css/u/uwdynnbji.css';
import '../../css/x/xnnhmccbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="cql1pwtbp"/><path class="uwdynnbji"/><path class="xnnhmccbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-broken" /></template>
