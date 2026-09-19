<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ohtunpb.css';
import '../../css/u/uxtfceu2g.css';
import '../../css/q/qcfr4vtpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ohtunpb"/><rect class="uxtfceu2g"/><path class="qcfr4vtpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bar-chart-big-filled" /></template>
