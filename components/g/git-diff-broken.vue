<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/ua_8dab4r.css';
import '../../css/p/pu5j3xbce.css';
import '../../css/x/x7p0rcbpv.css';
import '../../css/a/a5g7hqbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ua_8dab4r"/><path class="pu5j3xbce"/><path class="x7p0rcbpv"/><path class="a5g7hqbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-diff-broken" /></template>
