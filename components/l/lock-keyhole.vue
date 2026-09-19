<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m39im5btg.css';
import '../../css/i/irx-iw8lh.css';
import '../../css/u/u2ffjhxgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m39im5btg"/><path class="irx-iw8lh"/><circle class="u2ffjhxgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lock-keyhole" /></template>
