<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/apst68bcm.css';
import '../../css/v/v5dr9sbpb.css';
import '../../css/l/l0am3zboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apst68bcm"/><path class="v5dr9sbpb"/><path class="l0am3zboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-operator" /></template>
