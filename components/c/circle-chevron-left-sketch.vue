<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o7q1r2bvo.css';
import '../../css/t/ttgol1b5u.css';
import '../../css/c/cgfote1dz.css';
import '../../css/r/rhz0hmbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o7q1r2bvo"/><path class="ttgol1b5u wm-a"/><path class="cgfote1dz wm-k"/><path class="rhz0hmbrm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-left-sketch" /></template>
