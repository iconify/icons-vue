<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o_e9bzw-o.css';
import '../../css/o/oszh--blj.css';
import '../../css/h/hrr5vnrqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_e9bzw-o"/><path class="oszh--blj"/><path class="hrr5vnrqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-10" /></template>
