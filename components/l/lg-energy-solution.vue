<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frpgang2p.css';
import '../../css/g/gp6vekbyg.css';
import '../../css/q/qc-_kzt9w.css';
import '../../css/f/fmovjab8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":210,"height":26};
const content = `<path class="frpgang2p"/><path class="gp6vekbyg"/><path class="qc-_kzt9w"/><path class="fmovjab8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lg-energy-solution" /></template>
