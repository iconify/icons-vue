<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pw8f5c0fp.css';
import '../../css/d/de9gu_b1y.css';
import '../../css/z/z4jhrz2uf.css';
import '../../css/c/cs_1o3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pw8f5c0fp"/><circle class="de9gu_b1y"/><path class="z4jhrz2uf"/><path class="cs_1o3bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-linear" /></template>
