<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jjkk9fb5u.css';
import '../../css/m/ms46j986h.css';
import '../../css/a/a3r5tvbim.css';
import '../../css/u/ubx3racak.css';
import '../../css/s/sqvxsve2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jjkk9fb5u wm-k"/><path class="ms46j986h wm-shine"/><path class="a3r5tvbim wm-shine"/><path class="ubx3racak wm-deco"/><path class="sqvxsve2u wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:dumpling" /></template>
