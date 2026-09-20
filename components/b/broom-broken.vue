<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pz1slbcbq.css';
import '../../css/u/u154v_8wc.css';
import '../../css/x/xv6r26bwy.css';
import '../../css/d/d07orurwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pz1slbcbq"/><path class="u154v_8wc"/><path class="xv6r26bwy"/><path class="d07orurwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:broom-broken" /></template>
