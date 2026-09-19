<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/heyq2bc2u.css';
import '../../css/m/mrda_3qxu.css';
import '../../css/h/hjjceedbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="heyq2bc2u"/><path class="mrda_3qxu"/><path class="hjjceedbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:film-roll-02" /></template>
