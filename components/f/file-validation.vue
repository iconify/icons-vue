<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idcg027iu.css';
import '../../css/k/kh9rsjb-p.css';
import '../../css/v/v7xgjhbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idcg027iu"/><path class="kh9rsjb-p"/><path class="v7xgjhbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-validation" /></template>
