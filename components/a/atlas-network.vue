<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbvvl1bla.css';
import '../../css/t/thpm74blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wbvvl1bla"/><path class="thpm74blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atlas-network" /></template>
