<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s5vktnbeo.css';
import '../../css/u/unskt_bda.css';
import '../../css/t/tcghh8b0d.css';
import '../../css/m/mon8s9lvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s5vktnbeo"/><path class="unskt_bda"/><path class="tcghh8b0d"/><path class="mon8s9lvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:biometric-access" /></template>
