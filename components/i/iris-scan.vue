<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ajfenzn0j.css';
import '../../css/c/c6bmv3q-h.css';
import '../../css/h/hpbrvm4rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ajfenzn0j"/><path class="c6bmv3q-h"/><path class="hpbrvm4rm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:iris-scan" /></template>
