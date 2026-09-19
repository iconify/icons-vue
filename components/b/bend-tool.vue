<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pyd8uurcz.css';
import '../../css/i/i7327t3bx.css';
import '../../css/g/gtqacwbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="pyd8uurcz"/><circle class="i7327t3bx"/><path class="gtqacwbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bend-tool" /></template>
