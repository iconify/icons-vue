<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi1s0_b3l.css';
import '../../css/q/q25o2buzt.css';
import '../../css/d/df-2q4bmd.css';
import '../../css/h/hp_g0wb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi1s0_b3l"/><path class="q25o2buzt"/><path class="df-2q4bmd"/><path class="hp_g0wb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:categories-filled" /></template>
