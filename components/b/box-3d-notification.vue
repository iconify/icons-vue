<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vy973jzih.css';
import '../../css/s/sotccjbfo.css';
import '../../css/s/sklx66bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vy973jzih"/><path class="sotccjbfo"/><circle class="sklx66bfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-notification" /></template>
