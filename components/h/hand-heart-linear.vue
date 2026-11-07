<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/an1auylmc.css';
import '../../css/r/r_kt-dgff.css';
import '../../css/e/eck4ylbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="an1auylmc"/><path class="r_kt-dgff"/><path class="eck4ylbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-heart-linear" /></template>
