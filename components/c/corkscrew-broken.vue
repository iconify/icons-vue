<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rg5apqxys.css';
import '../../css/g/gi6nexo9p.css';
import '../../css/d/d4va52zkr.css';
import '../../css/l/lg1zcpg4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rg5apqxys"/><path class="gi6nexo9p"/><path class="d4va52zkr"/><path class="lg1zcpg4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-broken" /></template>
