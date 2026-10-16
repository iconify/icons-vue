<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdn_2wb2j.css';
import '../../css/n/nvz_g9bec.css';
import '../../css/p/pzwt5rb-f.css';
import '../../css/r/rzhih4b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdn_2wb2j"/><path class="nvz_g9bec"/><path class="pzwt5rb-f"/><path class="rzhih4b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-queue-20-bold" /></template>
