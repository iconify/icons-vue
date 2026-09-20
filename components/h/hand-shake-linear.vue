<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t7n_a516v.css';
import '../../css/r/rwyyhnb2f.css';
import '../../css/q/qgl0b2pvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t7n_a516v"/><path class="rwyyhnb2f"/><path class="qgl0b2pvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-shake-linear" /></template>
