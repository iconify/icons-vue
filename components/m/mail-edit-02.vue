<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mdbcilbso.css';
import '../../css/q/qonh3zbpu.css';
import '../../css/k/kj5sz9cps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mdbcilbso"/><path class="qonh3zbpu"/><path class="kj5sz9cps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-edit-02" /></template>
