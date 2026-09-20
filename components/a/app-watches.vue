<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltsvmv17u.css';
import '../../css/p/pvoys4t1r.css';
import '../../css/n/nr1kobbpa.css';
import '../../css/r/rgdhmtlro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ltsvmv17u"/><path class="pvoys4t1r"/><path class="nr1kobbpa"/><path class="ouiIcon__fillSecondary rgdhmtlro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-watches" /></template>
