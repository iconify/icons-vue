<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/d/d0koy98sj.css';
import '../../css/i/icu8aybza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="t_2lkqbxb"><path class="d0koy98sj"/><path class="icu8aybza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:cart" /></template>
