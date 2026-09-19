<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ijddvyb3m.css';
import '../../css/n/ny379ofjh.css';
import '../../css/b/b5koxcuah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ijddvyb3m"/><path class="ny379ofjh"/><path class="b5koxcuah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:building" /></template>
