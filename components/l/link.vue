<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pihk1kufz.css';
import '../../css/n/n9_obdcgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="pihk1kufz"/><path class="n9_obdcgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:link" /></template>
