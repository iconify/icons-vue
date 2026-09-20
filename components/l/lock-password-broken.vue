<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uwdynnbji.css';
import '../../css/x/xnnhmccbq.css';
import '../../css/e/eyig6k37j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uwdynnbji"/><path class="xnnhmccbq"/><path class="eyig6k37j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-password-broken" /></template>
