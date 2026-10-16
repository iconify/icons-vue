<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he0-9w7up.css';
import '../../css/g/gsa3x5b0c.css';
import '../../css/p/p2d0_rjcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he0-9w7up"/><path class="gsa3x5b0c"/><path class="p2d0_rjcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hybrid-inverter-48-bold" /></template>
