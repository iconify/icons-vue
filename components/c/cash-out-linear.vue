<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ntqzpqbnu.css';
import '../../css/i/i-b1b9mbj.css';
import '../../css/m/mssc0fbma.css';
import '../../css/z/zsvh3abtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ntqzpqbnu"/><path class="i-b1b9mbj"/><path class="mssc0fbma"/><path class="zsvh3abtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cash-out-linear" /></template>
