<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xktvohbrl.css';
import '../../css/m/m8l8w3o9n.css';
import '../../css/s/srykvsb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xktvohbrl"/><path class="m8l8w3o9n"/><path class="srykvsb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:french-fries-01" /></template>
