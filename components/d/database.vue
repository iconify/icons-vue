<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/a/a06nqacsr.css';
import '../../css/t/trlth4bch.css';
import '../../css/k/k_yyil5ms.css';
import '../../css/n/nf1dv4jjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="h_l78yaxm"/><path class="a06nqacsr"/><path class="trlth4bch"/><path class="k_yyil5ms"/><path class="nf1dv4jjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database" /></template>
