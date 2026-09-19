<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mme__qbhi.css';
import '../../css/l/l9s2l9b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mme__qbhi"/><path class="l9s2l9b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:info-square" /></template>
