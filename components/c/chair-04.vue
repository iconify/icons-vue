<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f9kkz6r8k.css';
import '../../css/x/x6_572bcm.css';
import '../../css/v/v2j04pb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f9kkz6r8k"/><path class="x6_572bcm"/><path class="v2j04pb6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chair-04" /></template>
