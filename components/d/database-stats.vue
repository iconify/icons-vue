<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v_wvpib4a.css';
import '../../css/m/mpo63bcwo.css';
import '../../css/n/nhfue6ory.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v_wvpib4a"/><path class="mpo63bcwo"/><path class="nhfue6ory"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:database-stats" /></template>
