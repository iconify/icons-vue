<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/d8wdw2bdw.css';
import '../../css/g/gmcwwh2ne.css';
import '../../css/v/vwqq62bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8wdw2bdw"/><rect class="gmcwwh2ne"/><rect class="vwqq62bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:decimals-arrow-right" /></template>
