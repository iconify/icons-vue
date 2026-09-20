<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xa_506f5h.css';
import '../../css/z/zz_qntbxb.css';
import '../../css/j/jh9foyc5c.css';
import '../../css/j/jtti8bn6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="zz_qntbxb"/><path class="jh9foyc5c"/><path class="jtti8bn6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-down-minimalistic-linear" /></template>
