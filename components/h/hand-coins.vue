<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o79j5mb4a.css';
import '../../css/s/sb8342bfd.css';
import '../../css/c/csq3qnmej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o79j5mb4a"/><path class="sb8342bfd"/><circle class="csq3qnmej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-coins" /></template>
