<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eoh47sb2n.css';
import '../../css/u/ue3e5g9-c.css';
import '../../css/d/d2r59cciv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eoh47sb2n"/><path class="ue3e5g9-c"/><path class="d2r59cciv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-lock-remove-02" /></template>
