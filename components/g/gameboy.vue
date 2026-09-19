<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/knpt5p59u.css';
import '../../css/o/oe7093-zs.css';
import '../../css/y/y9pit_b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="knpt5p59u"/><path class="oe7093-zs"/><path class="y9pit_b0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gameboy" /></template>
