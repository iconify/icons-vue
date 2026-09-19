<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m30is0msy.css';
import '../../css/q/qhz72-bbk.css';
import '../../css/s/somstlbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m30is0msy"/><path class="qhz72-bbk"/><path class="somstlbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:installing-updates-01" /></template>
