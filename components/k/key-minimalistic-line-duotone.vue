<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fvm71nh3d.css';
import '../../css/t/tmpf65c9n.css';
import '../../css/c/ckcnl295s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvm71nh3d"/><path class="tmpf65c9n"/><path class="ckcnl295s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-line-duotone" /></template>
