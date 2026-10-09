<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftc5aebjh.css';
import '../../css/f/fe1-tbc_v.css';
import '../../css/m/mhimm6b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftc5aebjh"/><path class="fe1-tbc_v"/><path class="mhimm6b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-water-48-bold" /></template>
