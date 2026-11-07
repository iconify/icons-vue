<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aqn8_gw_r.css';
import '../../css/f/fqu4-ynwx.css';
import '../../css/h/h3hjjdb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aqn8_gw_r"/><path class="fqu4-ynwx"/><path class="h3hjjdb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layout-freeform-broken" /></template>
