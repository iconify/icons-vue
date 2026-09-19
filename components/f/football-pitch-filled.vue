<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3l_pqbpb.css';
import '../../css/l/lkwmxcc_x.css';
import '../../css/n/nsfh04bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3l_pqbpb"/><path class="lkwmxcc_x"/><path class="nsfh04bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:football-pitch-filled" /></template>
