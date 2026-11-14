<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vuutrabsm.css';
import '../../css/w/wnran_bnw.css';
import '../../css/y/yn5soub3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vuutrabsm"/><path class="wnran_bnw"/><path class="yn5soub3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:collections-bookmark" /></template>
