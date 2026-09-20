<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zzi-2vfyi.css';
import '../../css/s/s9_zw2bis.css';
import '../../css/p/pm1ejrbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zzi-2vfyi"/><path class="s9_zw2bis"/><path class="pm1ejrbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-broken" /></template>
