<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dhw2-5_mu.css';
import '../../css/n/ncss8tx5f.css';
import '../../css/c/cb8u71hty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dhw2-5_mu"/><path class="ncss8tx5f"/><path class="cb8u71hty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-01" /></template>
