<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpk98bbzf.css';
import '../../css/a/aekvfuqpv.css';
import '../../css/o/o6vxk8b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpk98bbzf"/><path class="aekvfuqpv"/><path class="o6vxk8b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:framadate" /></template>
