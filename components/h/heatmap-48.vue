<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty1v2kbgc.css';
import '../../css/p/p1evydb5d.css';
import '../../css/t/t40ahpbrj.css';
import '../../css/g/gh94m7zjr.css';
import '../../css/a/adji7ccar.css';
import '../../css/y/yyuh1v55c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty1v2kbgc"/><path class="p1evydb5d"/><path class="t40ahpbrj"/><path class="gh94m7zjr"/><path class="adji7ccar"/><path class="yyuh1v55c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatmap-48" /></template>
